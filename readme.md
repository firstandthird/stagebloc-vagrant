## Setup

### Requirements
 - Vagrant / Virtualbox
 - bindfs virtualbox plugin `vagrant plugin install vagrant-bindfs`


 ### Setup
  - hostfile `192.168.42.122  local.theme-dev`
  - `git submodule update --init --recursive`
  - Delete stock themes `rm -rf theme-dev/themes`
  - Find the lines in `puphpet/config.yaml` pointing to `/change/me/...` and change it to the correct path on your machine.
  - Run `vagrant up`
  - Hit http://local.theme-dev/ and log in
