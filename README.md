
# Ansible Role: Multicast Relay

## Description

Ansible role to install [multicast-relay](https://github.com/alsmith/multicast-relay).


## Example Vars

```yml
---
multicast_relay_run: true

multicast_relay_interfaces:
  - enp3s0.210
  - enp3s0.205
  - enp4s0.215

multicast_relay_options: []

```


## Example Playbook

```yml
- hosts: all
  roles:
     - multicast-relay
```


### v1.0

- Initial git commit




## Author
* Lindsay Harvey

## License

This project is under the MIT License. See the LICENSE file for the full license text.

## Copyright

- Copyright (c) 2022 Lindsay Harvey
