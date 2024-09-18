Ansible Playbooks Repository
This repository contains a collection of useful Ansible playbooks that can be reused for various system configurations, upgrades, installations, and automations.

📂 Repository Structure
Each playbook is saved directly in the root directory of this repository.
Each playbook is named descriptively based on its function.
🔧 How to Use
To run a specific playbook, follow these steps:

Clone this repository:

`git clone https://github.com/yourusername/Ansible-playbook.git`
`cd Ansible-playbook`

Run the desired playbook using Ansible:

`ansible-playbook -i inventory playbook_name.yaml`
Use the --limit flag if you need to target specific hosts:

`ansible-playbook playbook_name.yml --limit target_host`

📋 Playbooks Available
Upgrade Java (11 to 17)

Filename: javaupgrade.yaml
Description: Removes Java 11 and installs Java 17, setting it as the default version.

Install Docker and jenkins
Filename: docker-and-jenkins.yaml
Description: Installs Docker and configures it on the target host.
Setup Nginx

Filename: setup_nginx.yaml
Description: Installs and configures Nginx on Ubuntu-based systems.

📝 How to Contribute

Feel free to submit pull requests with improvements, new playbooks, or fixes. Follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix:

`git checkout -b feature-branch`
Commit your changes:

`git commit -m "Add feature or fix"`
Push to your branch:

`git push origin feature-branch`

Open a pull request in GitHub.
