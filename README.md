# What is Harbor Portal?

> Harbor Portal is one of the main components of Harbor, a cloud native registry that stores, signs, and scans content.
>
> It is a graphical user interface to ease the management of images.

[https://github.com/goharbor/harbor](https://github.com/goharbor/harbor)

# TL;DR;

```bash
$ curl -LO https://raw.githubusercontent.com/bitnami/bitnami-docker-harbor-portal/master/docker-compose.yml
$ docker-compose up
```

# Why use Bitnami Images?

* Bitnami closely tracks upstream source changes and promptly publishes new versions of this image using our automated systems.
* With Bitnami images the latest bug fixes and features are available as soon as possible.
* Bitnami containers, virtual machines and cloud images use the same components and configuration approach - making it easy to switch between formats based on your project needs.
* All our images are based on minideb a minimalist Debian based container image which gives you a small base container image and the familiarity of a leading linux distribution.
* Bitnami container images are released daily with the latest distribution packages available.


> This [CVE scan report](https://quay.io/repository/bitnami/harbor-portal?tab=tags) contains a security report with all open CVEs. To get the list of actionable security issues, find the "latest" tag, click the vulnerability report link under the corresponding "Security scan" field and then select the "Only show fixable" filter on the next page.

# How to deploy Harbor in Kubernetes?

Deploying Bitnami applications as Helm Charts is the easiest way to get started with our applications on Kubernetes. Read more about the installation in the [Bitnami Harbor Chart GitHub repository](https://github.com/bitnami/charts/tree/master/bitnami/harbor).

Bitnami containers can be used with [Kubeapps](https://kubeapps.com/) for deployment and management of Helm Charts in clusters.

# Why use a non-root container?

Non-root container images add an extra layer of security and are generally recommended for production environments. However, because they run as a non-root user, privileged tasks are typically off-limits. Learn more about non-root containers [in our docs](https://docs.bitnami.com/containers/how-to/work-with-non-root-containers/).

# Supported tags and respective `Dockerfile` links

Learn more about the Bitnami tagging policy and the difference between rolling tags and immutable tags [in our documentation page](https://docs.bitnami.com/containers/how-to/understand-rolling-tags-containers/).


* [`1-ol-7`, `1.9.1-ol-7-r5` (1/ol-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-harbor-portal/blob/1.9.1-ol-7-r5/1/ol-7/Dockerfile)
* [`1-debian-9`, `1.9.1-debian-9-r4`, `1`, `1.9.1`, `1.9.1-r4`, `latest` (1/debian-9/Dockerfile)](https://github.com/bitnami/bitnami-docker-harbor-portal/blob/1.9.1-debian-9-r4/1/debian-9/Dockerfile)
* [`1-centos-7`, `1.9.1-centos-7-r0` (1/centos-7/Dockerfile)](https://github.com/bitnami/bitnami-docker-harbor-portal/blob/1.9.1-centos-7-r0/1/centos-7/Dockerfile)

# Configuration

Harbor Portal is a component of the Harbor application. In order to get the Harbor application running on Kubernetes we encourage you to check the [bitnami/harbor Helm chart](https://github.com/bitnami/charts/tree/master/bitnami/harbor) and configure it using the options exposed in the values.yaml file.

For further information about the specific component itself, please refer to the [source repository documentation](https://github.com/goharbor/harbor/tree/master/docs).

# Contributing

We'd love for you to contribute to this container. You can request new features by creating an [issue](https://github.com/bitnami/bitnami-docker-harbor-portal/issues), or submit a [pull request](https://github.com/bitnami/bitnami-docker-harbor-portal/pulls) with your contribution.

# Issues

If you encountered a problem running this container, you can file an [issue](https://github.com/bitnami/bitnami-docker-harbor-portal/issues). For us to provide better support, be sure to include the following information in your issue:

- Host OS and version
- Docker version (`docker version`)
- Output of `docker info`
- Version of this container (`echo $BITNAMI_IMAGE_VERSION` inside the container)
- The command you used to run the container, and any relevant output you saw (masking any sensitive information)

# License

Copyright (c) 2019 Bitnami

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
