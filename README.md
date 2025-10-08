# Ansible
##### Ansible is an open-source automation tool used for:
- **Configuration Management:** install and configure software on many servers.
- **Provisioning:** set up infrastructure automatically.
- **Application Deployment:** deploy code consistently.
- **Orchestration:** coordinate tasks across multiple systems.

## Key Components
**Component**	              **Description**
- **Control Node:**	        The system where Ansible is installed and commands are run
- **Managed Nodes:**	      Target machines that Ansible manages
- **Inventory:**	          List of target hosts (in a file or dynamic source)
- **Modules:**	            Reusable scripts that perform specific tasks (e.g., install packages, copy files)
- **Playbooks:**	          YAML files that define automation steps
- **Roles:**	              Organized, reusable collections of playbooks, tasks, templates, etc.
- **Facts:**	              Data Ansible gathers about systems (OS, IP, etc.)
- **Variables:**	          Dynamic values for customization

# Installation (Ubuntu Example)
```bash
sudo apt update
sudo apt install ansible -y

# Check if installed
ansible --version
```

# How It Works (Concept)
**Think of Ansible as a remote controller for servers:**
1. You write instructions in YAML (called playbooks).
2. You define which servers to manage in an inventory file.
3. You run a command like:
```bash
ansible-playbook playbook.yml -i inventory
```
4. Ansible connects via SSH (no agents needed) and executes the tasks.
