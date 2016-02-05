+++
title = "help"
description = "List the UCP commands"
[menu.ucp]
identifier="ucp_help"
parent = "ucp_ref"
+++

# help

Shows a list of UCP commands.

## Usage

```
docker run --rm -it \
     --name ucp \
     -v /var/run/docker.sock:/var/run/docker.sock \
     docker/ucp \
     help
```
