# AWX Playbook

Follows the official guide: https://github.com/ansible/awx/blob/devel/INSTALL.md

Clone the repo: `git clone https://github.com/calvinbui/awx-playbook.git && cd awx-playbook`

Update if needed: `git pull`

Install the roles: `ansible-galaxy install -r roles/requirements.yml --force`

Install sshpass: `sudo apt install sshpass -y`

Run the playbook: `ansible-playbook site.yml -i hosts -v -u calvin -k -K --ask-vault-pass`
