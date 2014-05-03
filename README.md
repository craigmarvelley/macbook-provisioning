macbook-provisioning
====================

A mirror of the Ansible scripts used to provision my Macbook, minus any private stuff.

See http://marvelley.com/blog/2014/04/11/local-provisioning-with-ansible/ for details.

## Commands

To run the playbook, run the following command within the macbook-provisioning directory.

    $ ansible-playbook playbook.yml -i hosts

To run a specific set of tasks, specify which tag using the -t option.

    $ ansible-playbook playbook.yml -i hosts -t homebrew
    $ ansible-playbook playbook.yml -i hosts -t zsh
    $ ansible-playbook playbook.yml -i hosts -t dotfiles