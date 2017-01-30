# Ansible scripts for setting up my little server

This repository holds the playbooks for installing and configuring all the different parts of my little server system. Variables are encrypted using vault.

## Installation

Install ansible to use

## Running playbooks

ansible-playbook name-playbook.yml -D -i hosts -l target-server -s -K --ask-vault-pass --check