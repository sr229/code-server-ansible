# code-server Ansible Playbooks

This playbooks deploy [code-server](https://github.com/codercom/code-server) to your machine, should you wish not to use Docker, and you want to automate deployments on a large scale.

## Running

Simply pick from the `playbooks/` directory. Keep in mind of these variants:

- `install-release.yml` installs the latest release in Coder. This is updated when there is new releases.

- `install-git.yml` installs from the master branch. This will install additional dependencies for building the git tree.

