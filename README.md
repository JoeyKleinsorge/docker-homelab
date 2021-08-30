# homelab

A repository to keep resources and configuration files used with my homelab containers.

[![version](https://img.shields.io/github/manifest-json/v/JoeyKleinsorge/homelab?label=Kubernetes)](https://github.com/JoeyKleinsorge/homelab/blob/master/VERSIONS.md)
[![license](https://img.shields.io/github/license/JoeyKleinsorge/homelab)](https://github.com/JoeyKleinsorge/homelab/blob/master/LICENSE)
[![last commit](https://img.shields.io/github/last-commit/JoeyKleinsorge/homelab)](https://github.com/JoeyKleinsorge/homelab/commits/master)
[![commit activity](https://img.shields.io/github/commit-activity/y/JoeyKleinsorge/homelab)](https://github.com/JoeyKleinsorge/homelab/commits/master)


# Content of the Repository

* [`dockerfile`](./homelab/) - YAML dockerfile that does all the work.
* [`env`](./example/) - Example configuration file.

# Pre-requisites

I do this all on my [Synology DS1817+] (https://global.download.synology.com/download/Document/Hardware/DataSheet/DiskStation/17-year/DS1817+/enu/Synology_DS1817_Plus_Data_Sheet_enu.pdf)

# Deployment
```
$ docker-compose -f homelab.yaml up -d
```

# Blog Posts

[blog] (https://joeykleinsorge.com)
