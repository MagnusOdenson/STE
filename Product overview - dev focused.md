<!-- this is product brief targeted to developer -->
<!-- omit in toc -->
## Table of content
1. [What is Mocker?](#what-is-mocker)
2. [How does Mocker work?](#how-does-mocker-work)
3. [How to deploy software?](#how-to-deploy-software)
   1. [Glossary](#glossary)

<!-- omit in toc -->
# Mocker - Product Overview

## What is Mocker?

Mocker is Platform-as-a-Service product that allows development teams to build, package and deploy applications. The core technology behind Mocker is open-source.

## How does Mocker work?

Mocker container is bundle of software, libraries, and configuration files. 

*Image* - template that is a basis of Mocker container. The Mocker image runs in as many containers as necessary, limited only by the cloud infrastructure.

To create Mocker images developer teams need to be familiar with JavaScript and have basic understanding of app containers. If you are not familiar with app containers, the Mocker foundation can  provide configuration templates.

Each Mocker image is defined in a Mockerfile. When container is created from Mocker image, all the resources are bundled and run on virtual machine dedicated only to that Mocker container.

Mocker can run on any cloud infrastructre.
>**NOTE**\
>At this point, Mocker is optimized for AWS, \
>because of this, Amazon and the Mocker foundation offer documentation for developer that are not familiar with AWS. 

## How to deploy software?

To deploy Mocker-based microservices: 
- Install the Mocker daemon that runs and orchestrates containers on a given software virtualization platform in the cloud
- Familiarize themselves with the structure of Mockerfiles 
- Familiarize themselves with the API of the Mocker daemon.

>**NOTE**\
>Unless customers pay to access Mocker's administrator tools, they will need to create their own scripts to control\
> the Mocker daemon and handle the initialization and shutdown of containers.

<br>

### Glossary

```
PaaS - Platform as a Service
Mockerfile - text file that defines the location of resources needed by the Mocker container
AWS - Amazon Web Service, Amazon's cloud based service platform
```