## Synopsis
Repository to 

## Code Example

Show what the library does as concisely as possible, developers should be able to figure out **how** your project solves their problem by looking at the code example. Make sure the API you are showing off is obvious, and that your code is short and concise.

## Motivation

A short description of the motivation behind the creation and maintenance of the project. This should explain **why** the project exists.

## Installation

### Clone repository created before
git clone git@github.com:vmorate/devops-test.git

### https://atlas.hashicorp.com/bento/boxes/centos-7.2
vagrant init bento/centos-7.2; vagrant up --provider virtualbox

### Add inline script to install puppet-agent
centos7.vm.provision "shell", inline: "sudo yum install puppet-agent"

### Search for the best Jenkins module in puppet forge https://forge.puppet.com

### Execute puppet module install to install jenkins module following the best module found https://forge.puppet.com/rtyler/jenkins
.\puppet.bat module install rtyler-jenkins --version 1.7.0 --modulepath 'C:\Users\Victor\Repositories\devops-test\modules\'

### Create yaml file for the vagrant box and add Jenkins class

## Tests

Describe and show how to run the tests with code examples.

## Contributors

Victor Morate

## License

Vagrant from HashiCorp, Puppet

