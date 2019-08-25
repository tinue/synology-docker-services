# Synology Storage Server
The Synology Diskstations can server more storage needs that the built-in apps allow. This project adda a few storage services based on docker images. Current content:
* [Portainer](https://www.portainer.io) Docker manager
* [Nexus](https://www.sonatype.com/nexus-repository-sonatype) Repository manager

![DevServer](screenshots/all-apps.png)
Note: I'll have to re-do the screenshot: Jenkins is no longer part of this project.

Click [here](INSTALL.md) for installation instructions.

# Release History
* 1.0.0, 2019-07-13: First version
* 2.0.0, 2019-08-25: Rename to "Synology Storage Server" and remove Jenkins (the Synology CPU is too weak for Jenkins)