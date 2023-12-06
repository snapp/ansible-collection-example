# Ⓐ Ansible Role: foo

This role provides ...

<!-- TODO: ## Requirements

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.
-->

<!-- TODO: ## Role Variables

 A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

An example variable.

  foo_variable1

Another example variable.

  foo_variable2
-->

<!-- TODO: ## Dependencies

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

None
-->

## Using this role in an Ansible playbook

The following example shows how this role can be defined in a playbook with parameters passed to override default variables.

> **INFORMATION**
> It is recommended that you use a Fully Qualified Collection Name (FQCN) when referencing your roles.
>
> For simplicity, this example shows the use of a role *without* a FQCN.

```yaml
---
- hosts: 'all'
  roles:
    - role: snapp.example.foo
      foo_variable1: true
      foo_variable2: false
      tags: snapp.example.foo
```

## Licensing

GNU General Public License v3.0 or later

See [LICENSE](https://www.gnu.org/licenses/gpl-3.0.txt) to see the full text.
