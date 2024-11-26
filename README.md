# NI SP Guides

Welcome to our collection of guides. Here you can find a very complete documentation and tools about NICE DCV, EF Portal, Authentication, SLURM etc and related services.

## Documentation

* [NI SP Knowledge base](https://www.ni-sp.com/knowledge-base/): A complete compilation about NICE DCV and EF Portal (EnginFrame) questions and tips and tricks
* [NICE DCV Download page](https://www.ni-sp.com/solutions/nice-dcv-download-page/): Download the NICE DCV binaries
* [NI SP Support page](https://support.ni-sp.com/): Open a ticket with NI SP Support team to get help with our services and scripts
* [NI SP Contact page](https://www.ni-sp.com/contact/): Send us an e-mail about everything

## Containers

We provide some ready to use containers that you can use to test our services.

* __EF Portal:__ [For Linux](https://github.com/NISP-GmbH/EF-DCV-Containers) A ready to use EnginFrame that can is integrated with Slurm, DCV Session Manager and SSSD (OpenLDAP and Active Directory).

## Scripts

We support a bunch of scripts that will help you to fastly get the services being installed and managed. And they are OpenSource! ;)

### NICE DCV

* __DCV Managament:__ [For Linux](https://github.com/NISP-GmbH/DCV-Management-Linux) and [For Windows](https://github.com/NISP-GmbH/DCV-Management-Windows) A powerful tool that will install an API service in your Linux that can control sessions (create, close, timeout) and create session during the login.

* __DCV Installer:__ [For Linux](https://github.com/NISP-GmbH/DCV-Installer) and [For Windows](https://www.ni-sp.com/knowledge-base/dcv-installation/windows/) An easy way to setup DCV Server (with and without GPU support), with Session Manager (Agent, Broker, CLI and Gateway)

* __DCV Log Rotation:__ [For Linux](https://github.com/NISP-GmbH/DCV-Log-Rotation) Log rotation script that will allow log rotation without restart DCV Server

* __Collect DCV Logs:__ [For Linux](https://github.com/NISP-GmbH/Collect-DCV-Logs) Are you having problem? This script will collect all relevant info about your DCV Server environment, so you can open a ticket and attach the generated file to help the support.

* __DCV Setup GUI:__ [For Windows][https://github.com/NISP-GmbH/Windows-DCV-Setup-GUI] Configure DCV Server and DCV Session Manager without have to manually edit Windows registries, using a visual interface.

### EF Portal

* __[Collect EF Portal Logs](https://github.com/NISP-GmbH/Collect-EF-Portal-Logs)__ Are you trying to troubleshoot an issue? This script will collect all relevant info about your EF Portal environment, so you can open a ticket and attach the generated file to help the support.
* __[Entra ID SSO](https://github.com/NISP-GmbH/EF-EntraID-SSO)__ A simple solution that will integrate Entra ID (that supports Windows Hello) and EF Portal (EnginFrame)

### Slurm

* __[Slurm Linux Installer](https://github.com/NISP-GmbH/SLURM)__ The fastest way to get Slurm installed in your environment.

### Reprise License Manager (RLM)

* __[RLM Linux Installer](https://github.com/NISP-GmbH/RLM_for_Linux)__ Can be used to provide, with public or private cloud, a way to storage, manage and activate licenses.

## Cloud services

* __AWS AMI NICE DCV images__ A ready-to-go way to get your NICE DCV under High End servers
