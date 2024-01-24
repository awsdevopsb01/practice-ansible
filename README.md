# practice-ansible

### YAML - Yet Another Markup Language
1. Yaml works on Indentation. Nothing but spacing. Must have uniform spacing.

Example:
name: Devops
  msg: [Hello, devops, aws]
  name : {
   Company name: [one, two],
   designation: devops engineer
   }
2. Coding patterns
[] - list
{} - map
3. Tab not allowed in Yaml.
4. Keys are provided by program(ansible, kubernetes)
5. sometimes we can create our own keys(like variables). Depends on the tool.
6. yaml files contains an extension of yaml, yml.

Ansible: 

Variables:

# variables are accessed using {{}}
# Ansible supports quotes, but not mandatory always.
# String - {{ Varaible }} - quotes not required
# {{ variable }} alone --> use either single quotes or double quotes
# variable created inside a task cannot be accessed by other tasks in the playbook.
# variable created on play level can be accessed by other tasks in the playbook.
# Var file concept is used on play level only. We can use var file on task level.