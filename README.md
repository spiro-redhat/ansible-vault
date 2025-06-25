Ansible playbook to install HashiCorp Vault on a RHEL 9 machine. Adjust to suit other environments. 


The **`firewalld`** module is part of the **`ansible.posix`** collection, which may not be installed by default in your environment. You need to install the collection if it is missing.

```bash 
ansible-galaxy collection install ansible.posix
```
- **Verify Installation:** After installation, you can verify if the `ansible.posix` collection is available:

```bash
ansible-galaxy collection list
```
