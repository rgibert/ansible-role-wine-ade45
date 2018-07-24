# WINE - Adobe Digital Editions 4.5.0

Ansible role to install the ADE 4.5.0 in WINE on Linux systems

## Requirements

- none

## Role Variables

| Variable | Default | Description |
|----------|---------|-------------|
| wine_ade45_prefix | ~/.wine-ade45 | Where to install ADE |
| wine_ade45_450_installer_path | /tmp/ADE_4.5.0_Installer.exe | Path to the ADE 4.5.0 installer |

## Dependencies

- none

## Example Playbook

```
- hosts:
    - servers
  roles:
    - role: rgibert.wine_ade45
```

## License

GPLv3

## Author Information

Richard Gibert <richard@gibert.ca>
