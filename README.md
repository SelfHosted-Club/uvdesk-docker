# uvdesk-docker
This is a Docker build for uvdesk, it runs and downloads version 1.1.0 from the stable releases from uvdesk.

Prebuilt docker images can be found at https://hub.docker.com/r/tivini/uvdesk/tags - choose the ones without the s3 in the tag name if you don't need the capability. 1.1.0-amd64 for pretty much all desktops and servers. 1.1.0-arm64v8 works on mac, if someone tests it on RaspberryPi and it works let me know.

These DO NOT include a database, and you will need an external one, this has been tested with MariaDB.


Based off https://github.com/uvdesk/community-skeleton
