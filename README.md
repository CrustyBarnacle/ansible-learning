## ansible-learning
Learning the Ansible way - node deploy, configure, and jupyter lab deployment

*NOTE*: Currently works on one cloud provisionaing service (https://cloud.linode.com/)
The *deploy_instance\*.yml* currently deploys a nano instance of _ubuntu22.04_.

### Because an online class
Since I was about to start working on [Python For Defenders](https://learn.taggart-tech.com/p/python-for-defenders-pt1), why not make this an opportunity for another project, and automate deploying the [lab environment](https://github.com/The-Taggart-Institute/python-for-defenders) for the class? :-D

### TODO
* systemd unit file for *jupyter_lab* service
  * [How to run Jupyter Lab as systemd service, *TechOverflow*](https://techoverflow.net/2021/06/11/how-to-run-jupyter-lab-as-systemd-service/)
  * [Ansible Docs - systemd](https://docs.ansible.com/ansible/2.9/modules/systemd_module.html)
* UFW - allow access to Jupyter Lab
* ansible task for *jupyter_lab* service
  * Install and enable (daemon-reload)
  * Start service

### References
#### Ansible
* [How to Use Ansible to Automate Initial Server Setup on Ubuntu 20.04, *Digital Ocean - Ansible Docs*](https://www.digitalocean.com/community/tutorials/how-to-use-ansible-to-automate-initial-server-setup-on-ubuntu-20-04)
* [Ansible Playbook Docs](https://docs.ansible.com/ansible/latest/playbook_guide/index.html)
* [Ansible Modules Index is your friend!](https://docs.ansible.com/ansible/latest/collections/index_module.html)
#### Jupyter Notebook/Lab
* [Running a public notebook server, *Jupyter Notebook Docs*](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html#running-a-public-notebook-server)
#### Poetry - may your Python roll trippingly...
