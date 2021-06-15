# Fedora-wizard

This repository is used to manage my Fedora machine.
The idea was taken from [geerlingguy's mac-dev-playbook](https://github.com/geerlingguy/mac-dev-playbook).

## Quickstart

    git clone git@github.com:Nequo/fedora-wizard.git
    cd fedora-wizard
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt
    ansible-playbook main.yml --ask-become-pass
