# ansible-sysmon

An Ansible role for installing and configuring sysmon

## Sysmon Configuration

The role downloads and applies the [SwiftOnSecurity sysmon config](https://github.com/SwiftOnSecurity/sysmon-config).

## OS Platforms

This role has been tested on the following operating systems:

- Ubuntu 18.04

## Usage

To use this role in your playbook, add the code below:

```
- name: Install Sysmon
  import_role:
    name: ansible-sysmon
```

## Disclaimer

This role is meant for use in the SANS 699 course and is provided as is.

## License

[MIT](LICENSE)

