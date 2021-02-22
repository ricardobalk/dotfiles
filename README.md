# ricardobalk/dotfiles

These are my dotfiles. I use it in combination with my [Ansible Playbooks][] to set up new systems and keep the configuration the same among all of my computers.

## Installation

The most easy and recommend way of installing these dotfiles is as follows:

- Clone this repository, obviously

- Set your own preferences (e.g. PGP key used by default). :wink:

- Use `lndir` from `xutils-dev` to automatically create symlinks from the same underlying directory structure.

  ```sh
  sudo apt update
  sudo apt install xutils-dev
  lndir '/path/to/this/repository/' "$HOME"
  ```

[Ansible Playbooks]: https://github.com/ricardobalk/ansible "Ricardo's Collection of Ansible Roles, Tasks and Playbooks"
