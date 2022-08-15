[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
  <a href="https://github.com/95jonpet/playbooks">
    <img src="images/logo.svg" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Peter Jonsson's Playbooks</h3>

  <p align="center">
    A collection of Ansible playbooks for environment automation.
    <br />
    <a href="https://github.com/95jonpet/playbooks/issues">Report Bug</a>
    ·
    <a href="https://github.com/95jonpet/playbooks/issues">Request Feature</a>
  </p>
</div>

## About The Project

This repository contains a collection of Ansible playbooks for automating various environment configuration tasks.

## Getting Started

To get a local copy up and running follow these simple example steps.

1. Install _Ansible_ using the [Installing Ansible guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html).

2. Clone the repo.

   ```bash
   git clone https://github.com/95jonpet/playbooks.git
   ```

## Usage

Run the playbooks using the `ansible-playbook` command and a personal `inventory.yaml` file.

```bash
ansible-playbook infrastructure.yaml -i inventory.yaml
```

An example `inventory.yaml` file:

```yaml
all:
  hosts:
    myserver-1:
    myserver-2:
```

## Roadmap

- [ ] Nginx reverse proxy.
- [ ] SSL certificates.

See the [open issues](https://github.com/95jonpet/playbooks/issues) for a full list of proposed features (and known issues).

## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

[contributors-shield]: https://img.shields.io/github/contributors/95jonpet/playbooks.svg?style=for-the-badge
[contributors-url]: https://github.com/95jonpet/playbooks/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/95jonpet/playbooks.svg?style=for-the-badge
[forks-url]: https://github.com/95jonpet/playbooks/network/members
[stars-shield]: https://img.shields.io/github/stars/95jonpet/playbooks.svg?style=for-the-badge
[stars-url]: https://github.com/95jonpet/playbooks/stargazers
[issues-shield]: https://img.shields.io/github/issues/95jonpet/playbooks.svg?style=for-the-badge
[issues-url]: https://github.com/95jonpet/playbooks/issues
[license-shield]: https://img.shields.io/github/license/95jonpet/playbooks.svg?style=for-the-badge
[license-url]: https://github.com/95jonpet/playbooks/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/95jonpet
