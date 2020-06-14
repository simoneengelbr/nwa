# Neighborhood Watch Alarm (NWA)
NWA is an open source neighborhood security movement with an alarm system that anyone can assemble and manage locally. NWA is published under the [MIT License](https://github.com/simoneengelbr/nwa/blob/master/LICENSE).

The client-server system consists of Arduino-based **alarms** outfitted with sensors, and a Raspberry Pi **server**. The devices communicate via LoRa signals and a TTN Gateway. The server sends text-messages when an alarm is triggered.

For general and installation related information, please see the [**main site**](https://nwa-site.herokuapp.com/) **NB** this site is under construction and the first version will be ready at the end of June 2020.

For system details and architecture descriptions, please see the [wiki](https://github.com/simoneengelbr/nwa/wiki).

# Code Status

All accepted source code goes through a **Continues Integration** pipeline using *Github Actions*.

The current status for the different pipelines can be seen below:

Alarm status:

![Arduino alarm-system/alarm CI](https://github.com/simoneengelbr/nwa/workflows/Arduino%20alarm-system/alarm%20CI/badge.svg)

Server status:

![Java/Maven alarm-system/server CI](https://github.com/simoneengelbr/nwa/workflows/Java/Maven%20alarm-system/server%20CI/badge.svg)

Frontend status:

![Node.js site/frontend CI](https://github.com/simoneengelbr/nwa/workflows/Node.js%20site/frontend%20CI/badge.svg)

Backend status:

![Node.js site/backend CI](https://github.com/simoneengelbr/nwa/workflows/Node.js%20site/backend%20CI/badge.svg)


# Current Project Team Members
## Maintainers
* [simoneengelbr](https://github.com/simoneengelbr)
* [mikkelgthang](https://github.com/mikkelgthang)
