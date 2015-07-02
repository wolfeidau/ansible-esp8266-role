# esp8266

This role installs all the esp8266 development environment.

## Example 

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: wolfeidau.esp8266, deploy_user: "markw" }

# Docker

This is also used to produce a docker container with this environment packed inside to make it easy for others to get building with esp8266!

To release a new version run the following commands:

    docker build -t wolfeidau/esp8266-dev:1.1.0
    docker tag -f wolfeidau/esp8266-dev:1.1.0 wolfeidau/esp8266-dev:latest
    docker push wolfeidau/esp8266-dev:1.1.0
    docker push wolfeidau/esp8266-dev:latest

# License

This code is Copyright (c) 2014 Mark Wolfe and licenced under the MIT licence. All rights not explicitly granted in the MIT license are reserved. See the included LICENSE file for more details.

# Author Information
------------------

Mark Wolfe <mark@wolfe.id.au>
