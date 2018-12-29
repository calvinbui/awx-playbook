# AWX Playbook

Follows the official guide: https://github.com/ansible/awx/blob/devel/INSTALL.md

Install the roles: `ansible-galaxy install -r roles/requirements.yml --force`

Run the playbook: `ansible-playbook site.yml -i hosts -v -u calvin -k -K`
