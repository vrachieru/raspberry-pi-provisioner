<p align="center">
    <img src="https://user-images.githubusercontent.com/5860071/47363006-704d5480-d6de-11e8-8322-96d150daec11.png" width="150px" />
    <br/>
    Setup Raspberry Pis with ease using Ansible.
</p>

This is a small collection of Ansible playbooks, templates and tasks for setup and configuration of my assorted raspberry pi boards and projects.

### Install

1. Clone and setup the ansible script. `git clone git@github.com:vrachieru/raspberry-pi-provisioner.git`

2. Set up an Ansible [inventory file](http://docs.ansible.com/intro_inventory.html) similar to the included hosts.example.  
  
3. Run `ansible-playbook -i <inventory_file> playbooks/playbook.yml` and wait for your the magic to happen!


### Requirements

[Ansible](http://www.ansible.com/) is required.

### License

MIT