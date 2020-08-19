# Role Name

This role will install nodered as a docker container on your system.

## Requirements

- Docker
- NodeJS

## Role Variables

nodered_image (nodered/node-red): The image that is used to run nodered.

nodered_port (1880): The port that will be exposed
nodered_service_name (nodered): The service name.
nodered_volume (nodered): The volume name that nodered is using.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - svenfinke.nodered_docker

## License

MIT