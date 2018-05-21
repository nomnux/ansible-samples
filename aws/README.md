# Ansible AWS module samples

## Requirements

* Ansible
* Python boto, boto3
* AWS credentials
    * ~/.aws/config
    * ~/.aws/credentials

## Installation

```
$ pip install ansible boto boto3 [--user]
```

## Usage

Create IAM group.

```
$ ansible-playbook iam-group.yml
```

Create Route 53 Hosted Zone and record set

```
$ ansible-playbook route53.yml
```
