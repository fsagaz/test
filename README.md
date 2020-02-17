# Ansible Styleguide

## Table of Contents
  
  1.Como deben nombrarse las variables

  
Usar `snake_case` para el nombre de las variables.

```yaml
# mal
- name: 'set some facts'
  set_fact:
    myBoolean: true
    myint: 20
    MY_STRING: 'test'

# bien
- name: 'set some facts'
  set_fact:
    my_boolean: true
    my_int: 20
    my_string: 'test'



