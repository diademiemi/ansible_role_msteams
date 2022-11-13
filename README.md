# Ansible Role Microsoft Teams
This is an Ansible role that installs Microsoft Teams on Linux. It can use the RPM, Deb or unofficial Flatpak package.  

Tested on Fedora 36 and Ubuntu 22.04, should work on any Linux distribution that the MS Teams packages or Flatpak package installs.  

## Requirements

### Base requirements
None  

## Variables
| Variable | Default | Description |
|----------|---------|-------------|
| `msteams_version` | `1.5.00.23861` | Version of Teams to install. |
| `msteams_package_format` | `rpm` for RedHat, `deb` for Debian, falls back to `flatpak` | How to install the package. To use `flatpak` you need `flatpak` installed. |
