---
layout: post
title:  "Containers"
---

### Machines pipeline

> Many deployments requires machine images for different server roles like applications and services,
> databases, and reverse proxies. Because building a machine image from scratch,
> using an operating system ISO and provisioning scripts,
> can take a considerable amount of time it can be useful to create a build pipeline for machine images. The first stage in the pipeline sets up a base image according to general standards in the organization. Subsequent stages can then enhance the base image for different purposes. If several applications or services have similar requirements,
> an application server for example, the pipeline can be extended by an intermediate stage,
> which takes the base image and provides an image with an application server but no application/service. These pipelines are not linear,
> they are trees that are branching out from the base image.

from radar
