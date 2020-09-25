# Personal machine setup with Ansible

Used to bring up a new machine (purchased or reimaged) to the state I want.

That said, the following are to be performed on the target machine:

## Prerequisites
* Ansible installed and globally visible
   * `sudo apt install python3 python3-pip`
   * `pip3 install ansible`
* Linux brew installed: `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"`
* Ansible community collection for interacting with brew: `ansible-galaxy collection install community.general`

## Run

`sudo ansible-pull -U https://github.com/tgmachina/personal-ansible.git`
