# ansible


#### before ansible.cfg
    ansiblansible all --key-file ~/.ssh/ansible -i inventory -m ping

#### after ansible.cfg
    ansible all -m ping

#### gather info from servers 
    ansible all -m gather_facts

### list all hosts
    ansible all --list-hosts
