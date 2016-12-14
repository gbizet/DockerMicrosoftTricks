---
title: Tips & Tricks to operate Docker on Microsoft
description: Here you can find some projects and files to help you deploy and manager Docker on Microsoft stack, Azure and on premises
keywords: docker, datacenter, install, orchestration, management, azure, swarm, microsoft, windows
---
Table of Contents
=================

   * [Easy Off/Online install of CS Docker Engine on Windows Server](#easy-offonline-docker-install-on-windows)

### Easy OffOnLine Docker Install on Windows

* Docker is not preinstalled on Windows Server 2016. Before installing it, you need to install the container service, and then download the docker package, install it and create the windows service.

* The DockerWindowsOfflineInstall folder contains a simple Powershell script to install and configure Docker on a Windows Server. It can be used Online, or in an Offline mode by download the package prior installing and put it in the right folder for the script to find it
