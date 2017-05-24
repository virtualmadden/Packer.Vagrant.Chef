# Packer.Vagrant.Chef
Templates for building Vagrant base boxes with Packer and Chef.

## Requirements
[Packer](https://www.packer.io/) - Tested with version 1.0.0

[Hyper-V](https://www.microsoft.com/en-us/cloud-platform/server-virtualization) - Tested with Windows 10 version 1703

[Chef](https://downloads.chef.io/) - Tested with version 1.4.3

## Usage
`> packer validate Windows10ExterpriseEditionEval1703.json`

`> packer build Windows10ExterpriseEditionEval1703.json`

## Testing
`> vagrant up`
