# get-asg-of-elb

Get the ASG of an ELB


## Role Variables

* `elb`      : Dictionary with the information of the Elastic Load Balancer
  * `name`   : Elastic Load Balancer name
  * `region` : Elastic Load Balancer region

## Example playbook

```yaml
- hosts: localhost
  connection: local
  gather_facts: no
  roles:
    - get-asg-of-elb
```

## License

GPLv2

## Author Information
jamatute (jamatute@paradigma)
