---
title: Docker Trusted Registry system requirements
description: Learn about the system requirements for installing Docker Trusted Registry.
keywords: DTR, architecture, requirements
---

Docker Trusted Registry can be installed on-premises or on the cloud.
Before installing, be sure your infrastructure has these requirements.

## Software requirements

You can install DTR on-premises or on a cloud provider. To install DTR,
all nodes must:
* Be managed by a Docker Universal Control Plane deployment,
* Have a fixed hostname.

## Ports used

When installing DTR on a node, make sure the following ports are open on that
node:

| Direction | Port    | Purpose                               |
|:---------:|:--------|:--------------------------------------|
|    in     | 80/tcp  | Web app and API client access to DTR. |
|    in     | 443/tcp | Web app and API client access to DTR. |

These ports are configurable when installing DTR.

## Compatibility and maintenance lifecycle

Docker Enterprise Edition is a software subscription that includes 3 products:

* Docker Engine EE,
* Docker Trusted Registry,
* Docker Universal Control Plane.

[Learn more about the maintenance lifecycle for these products](http://success.docker.com/Get_Help/Compatibility_Matrix_and_Maintenance_Lifecycle).

## Where to go next

* [DTR architecture](../../architecture.md)
* [Install DTR](index.md)
