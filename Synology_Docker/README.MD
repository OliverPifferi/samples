# Docker-scripts
In this folder you will find several Docker-commands that can be run as a simple user script/task on supported Synology-NAS assuming your configuration is placed into /volume1/docker/[application] where /volume1 is your Synology-volume (should be standard) and /docker the specific share.

All specific configuration is placed in a single folder on this share, for example "homeassistant" which would result in the path /volume1/docker/homeassistant.

Running these scripts will result in fetching the latest Docker image and instantly start those.

To see whether your Synology-model is supported to run Docker or not, see the Hardware Compatibility List at https://www.synology.com/en-us/dsm/packages/Docker?os_ver=7.0&search=docker!

