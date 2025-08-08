# Infra

This folder contains the main automation scripts and configuration to bootstrap a software factory environment.

## Features

- **Packer Automation**: Build Alpine Linux images using VirtualBox and Packer.
- **Vagrant Integration**: Use Packer-built images with Vagrant to provision Docker Compose hosts or (WIP) Kubernetes clusters.
- **Script Library**: Includes scripts for network, SSL, and environment configuration.
- **Extensible**: With the FrenchExDev.PoSh module ecosystem, you can write your own Packer and Vagrant multi-machine automated setup scripts.

## Structure

- `src/` — Infrastructure configuration and templates.
- `test/` — Test environments and Vagrantfiles.
- Main scripts for building, configuring, and managing your infrastructure.

## Usage

Run the provided PowerShell scripts to automate image creation and environment provisioning for your development