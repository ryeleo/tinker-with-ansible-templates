This is a simple little example to test out Ansible's template module.
With ansible installed, you can easily run this playbook to play with your Jinja templates.

## Prerequisites:

* Ansible
* (Jinja2, which Ansible already depends on)

## Example

Simply copy the template you are testing into the template file "mytemplate.j2", then run the playbook.

    ansible-playbook test-mytemplate.yml

> You can add variables as needed into the task in the playbook, similar to the 'sequence' variable.