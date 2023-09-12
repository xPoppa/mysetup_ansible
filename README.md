Check whether laptop has nvidia drivers
- install pyenv first. https://github.com/pyenv/pyenv#installation

- install ansible
    - install pipx `pip install --user pipx`
    - install ansible `pipx install ansible-core=2.13.6`
    - install community.general `ansible-galaxy collection install community.general`

- make user ask never passwd when doing sudo
    - `sudo visudo`
    - in the bottom of the file:
        - `$USER ALL=(ALL) NOPASSWD: ALL`
- install dbeaver via pop store
- install slack via pop store
- install brave via pop store
- install 1password via popstore
- install install discord via pop store

- add keys
- run playbook
    - `ansible-playbook linux-setup.yml`
