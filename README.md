# kali-build

kali-build is my custom Ansible playbook, designed to deploy my ideal Kali Linux environment.

## Requirements

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install ansible.

```bash
python3 -m pip install ansible
```

## Usage

```bash
git clone https://github.com/wither/kali-build.git
cd kali-build
ansible-playbook main.yml
```

## Credits

Credit to @ippsec for the a lot of the code for the [browser][https://github.com/wither/kali-build/tree/master/roles/browser] role.

## License

[MIT](https://choosealicense.com/licenses/mit/)
