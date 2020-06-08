# This is to create an EC2 insctance from ansible

## Pre-requisites

- Ansible
- Amazon Web Service

## The playbook

You may need to edit some things on the playbook.yml:

```yaml
image: <'image type eg: ubuntu'>
group: <security group>
vpc_subnet_id: <subnet>
```

## To run

```bash
ansible-playbook playbook.yaml
```