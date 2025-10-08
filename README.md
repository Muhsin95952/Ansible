# Ansible
##### Ansible is an open-source automation tool used for:
- **Configuration Management:** install and configure software on many servers.
- **Provisioning:** set up infrastructure automatically.
- **Application Deployment:** deploy code consistently.
- **Orchestration:** coordinate tasks across multiple systems.

## Key Components
**Component	              Description**
- **Control Node**	      The system where Ansible is installed and commands are run
- **Managed Nodes**	      Target machines that Ansible manages
- **Inventory**	          List of target hosts (in a file or dynamic source)
- **Modules**	            Reusable scripts that perform specific tasks (e.g., install packages, copy files)
- **Playbooks**	          YAML files that define automation steps
- **Roles**	              Organized, reusable collections of playbooks, tasks, templates, etc.
- **Facts**	              Data Ansible gathers about systems (OS, IP, etc.)
- **Variables**	          Dynamic values for customization
