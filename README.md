# sleif.nginx_container

This role runs an nginx instance on docker.

## Requirements

None

## Role Variables

- container_storage_dir_base: '/srv'

## Dependencies

None

## Example Playbook

    - hosts: "server"
      user: root
      # vars:
      #   DOCKER_NETWORK_NAME: 'custom_docker_network'
      roles:
        - { role: sleif.nginx_container, tags: "nginx_container" }

## License

MIT

## Author Information

Created in 2021 by Sebastian Berthold
