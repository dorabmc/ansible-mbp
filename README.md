# ansible-mbp
Ansible setup for the MC mbp

# Setup instructions

## Install brew

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

## Install Xcode

Try running `brew`.  It should prompt you to install Xcode.  If not,
install Xcode explicitly.

    xcode-select --install

## Install Ansible

    brew install ansible

## Run ansible

    ansible-playbook mbp.yml

