Docker install (docker + compose + machine)
-------------------------------------------
  - Connection = sudo user

1. Docker

	`ansible-playbook [-e state=uninstall] [-i inventory/hosts] [--become] [--ask-become-pass] --tags docker-install docker_install.yml`

2. Docker Compose

	`ansible-playbook [-e state=uninstall] [-i inventory/hosts] [--become] [--ask-become-pass] --tags docker-compose-install docker_install.yml`

2. Docker Machine

	`ansible-playbook [-e state=uninstall] [-i inventory/hosts] [--become] [--ask-become-pass] --tags docker-machine-install docker_install.yml`
