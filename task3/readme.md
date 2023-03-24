In task 3 the role is created with task to run aws command
default variables are declared in default directory(which has one key as format:json)

This role is ran using caller_playbook
The caller playbook uses the custom variables from custom_variables.yml file.
we can override all default variables from custom variables(currently farmat is updated to table instead of json)