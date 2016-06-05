# ansible-bootstrap
Set up host for ansible usage

## Description
This playbook handles user creation, generation of ssh key and sudo config for starting to use a host with ansible.

## Installation

Clone this repo into your directory of roles:

    mkdir roles
    git clone https://github.com/fheinle/ansible-bootstrap.git roles/bootstrap

Create a directory to hold ssh keys:

    mkdir authorized_keys

… or override the default path by passing a ``ssh_keyfile`` variable to the role.
