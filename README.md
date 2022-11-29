Prerequisites
```commandline
pip install --upgrade pip
mkdir projects/ansible
apt install python3.8-venv
python3 -m venv venv --prompt="Ninja wk2"
pip install ansible pyvmomi
pip install --upgrade setuptools==62.0.0
pip install --upgrade git+https://github.com/vmware/vsphere-automation-sdk-python.git

```

This is not yet working:

Install Python and Create Virtual Environment
```commandline
pip install --upgrade pip
mkdir projects/ansible
apt install python3.8-venv
python3 -m venv venv --prompt="ansible"
pip install -r requirements.txt
```

Install Ansible collections
```commandline
cd ansible/collections

```