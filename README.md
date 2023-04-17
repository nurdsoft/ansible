
# ansible 

## Assignment

1. Create an Ansible Playbook to install HashiCorp Terraform and Vault on a Linux OS.
    - Bonus: Check for existing installation/s.
2. Provide step/s to test the Playbook **locally**.
    - Bonus: Leverage a unit testing framework.
3. Create an Ansible Task inside of a Role which runs an AWS command with arguments as key-value pairs. The Task should define a default key-value pair and allow the caller (i.e. Playbook) to override the defaults.
E.g.:
```yaml 
# Role
- name: Task
  command: <command>
  vars:
      .....

# Playbook
- role: role-name
  vars:
      .....
```

## What to Submit

1. [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) `main` in this repo to your own namespace.
2. Create a new branch in your repo with the name: `<your_github_username>`.
3. Submit a [PR](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) from your forked repo into the `main` branch of this repo.

