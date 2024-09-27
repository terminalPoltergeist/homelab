# The terminalPoltergeist Homelab

## About

This repository is the remote origin for my infrastructure-as-code files and desired state configurations.

Files containing sensitive data have been ignored by git. I have tried to add documentation where necessary to fill in the gaps. I do not maintain this repository as a plug-and-play solution for other environments.

## Usage

- To run roles tagged with `never`, supply the role's named tag. (ie. if role zsh is tagged never, run the playbook with `--tags zsh` which will override the `never` tag)
