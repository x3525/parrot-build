Create a virtual environment and activate it (`externally-managed-environment`):

```bash
python -m venv venv
source venv/bin/activate
```

Install Ansible and clone this repo:

```bash
python -m pip install ansible
git clone https://github.com/x3525/parrot-build.git
```

Get sudo token and run Ansible playbook to execute the defined tasks:

```bash
cd parrot-build
sudo whoami
ansible-playbook main.yml
```
