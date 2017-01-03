Docker install (docker + compose + machine)
-------------------------------------------
  - Connection = sudo user

1. Docker

	`ansible-playbook -i hosts --become --ask-become-pass --tags docker-install docker_install.yml`

2. Docker Compose

	`ansible-playbook -i hosts --become --ask-become-pass --tags docker-compose-install docker_install.yml`

2. Docker Machine

	`ansible-playbook -i hosts --become --ask-become-pass --tags docker-machine-install docker_install.yml`
