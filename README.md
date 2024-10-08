# kali-build

kali-build is my custom Ansible playbook, designed to deploy my ideal Kali Linux environment.

![](./kali-build-screenshot.png)

## Requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install ansible.

```bash
python3 -m pip install ansible
```

## Usage

```bash
git clone https://github.com/wither/kali-build.git
cd kali-build
sudo whoami
ansible-playbook main.yml
```

## Features

- [pimpmykali](https://github.com/Dewalt-arch/pimpmykali) support.
- Neovim configuration with [NvChad](https://nvchad.com/).
- Burp Suite configuration and certificate support.
- "One Dark" theme across my favourite applications.
- [Tmux](https://github.com/tmux/tmux), [Alacritty](https://github.com/alacritty/alacritty) & zsh configuration.
- Firefox-ESR configuration including extensions, themes, settings and bookmarks.
- Installs my Obsidian [notes](https://github.com/wither/notes).
- and more!

## Credits

Credit to [IppSec](https://github.com/IppSec) for a lot of the code for the [browser](https://github.com/wither/kali-build/tree/master/roles/browser) role.

## License

[MIT](https://choosealicense.com/licenses/mit/)
