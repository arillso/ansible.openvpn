# Ansible Role: openvpn

## Description

Configurate your OpenVPN Client

## Installation

```bash
ansible-galaxy install arillso.openvpn
```

## Requirements

None

## Role Variables

| Variable             | Default     | Comments (type)                                   |
| :---                 | :---        | :---                                              |
| openvpn_name | openvpn | |
| openvpn_remote | | |
| openvpn_route | [] | |
| openvpn_verifyx509name | | |
| openvpn_cert | | |
| openvpn_tlsauth | | |
| openvpn_ca | | |
| openvpn_key | | |
| openvpn_client_as_service | false | defines if Openvpn runs as service |

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
     - arillso.openvpn
```

## Changelog

### 1.1

* add support Openvpn runs as service.

### 1.0

* inital role
* windows support

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher