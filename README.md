# Setup
```
git clone https://github.com/Pristavkin/aci-ansible.git
cd aci-ansible
mkvirtualenv -a $(pwd) -r requirements.txt aci-ansible
ansible-galaxy collection install cisco.aci
```

# Usage
1. Edit apic dictionary in the inventory file.
2. Run ```ansible-playbook make_some_magic.yml``` for deploy test configuration
3. Run ```ansible-playbook query_tennants.yml``` for retrive all tennants configuration
4. Try other query_... playbooks
