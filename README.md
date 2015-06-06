# Go Continuous Delivery Server Image

> [Go CD](http://www.go.cd/) server machine image

## Motivation

To get the latest version of the Go CD server setup with minimal effort by providing a machine image of a Go CD server.

## Requirements

* [ChefDK](https://downloads.chef.io/chef-dk/)
* [Packer](https://www.packer.io/)
* [Vagrant](https://www.vagrantup.com/)
* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

## Installation

1. Install the requirements listed above
2. Run ```./go build```
3. Run ```./go deploy```
5. Visit [http://192.168.0.1:8153](http://192.168.0.1:8153)

## Usage

    Usage: ./go <command>
    
    Available commands are:
        build        Build image
        deploy       Deploy image to local virtual machine
        destroy      Destroy local virtual machine

## Author

Jen Scobie (jenscobie@gmail.com)