# Vagrant Demo
This demo build a basic Ubuntu LAMP stack virtual machine using the following software versions:
 * Apache 2.4
 * MySQL 5.7
 * PHP 5.6

## Purpose
By using Vagrant, Virtualbox, and Git, each student gets:
  - A portfolio of their achievements while studying software development.
  - Self-service environment provisioning.  No waiting on IT support.
  - An environment devoid of side effects caused by other students
  - A simplified, uniformed troubleshooting experience:
    - The username is always `vagrant`
    - The testing URL is always `http://localhost:8080`
    - Students have complete access to their testing machine, meaning they can
      read server logs, experiment with the system software, or do whatever they want.

Bugs in the demo?  Students can feel free to submit pull requests for peer review.

## Prequisites
Some software **must** be installed prior to building an environment:

  - [git](https://git-scm.com/downloads)
  - [virtualbox](https://www.virtualbox.org/)
  - [vagrant](https://vagrantup.com/)

Here is a list of suggested IDEs for developing:
  - [atom](https://atom.io)
  - [rstudio](https://www.rstudio.com)
  - [sublime text](https://sublimetext.com)
  - [vim](https://vim.org)

## Quick Start
```
git clone https://github.com/ivytech-infrastructure/vagrant-demo.git
cd vagrant-demo
vagrant up
```

Once the machine has finished building you can connect using the following command:
```
vagrant ssh 
```

Note: The above `vagrant up` command will trigger Vagrant to download the `ubuntu/bionic` box via the specified URL.
Vagrant only does this if it detects that the box doesn't already exist on your system.

## Getting Started Guide
First you will need to [register](https://github.com/join/) an account on GitHub.  Once you have registered an account,
you will need to configure git.

```
git config --global user.name "firstName lastName"
git config --global user.email "username@ivytech.edu"
```

## Troubleshooting
### Git
If you have any issues with Git or learning how to use Git, head over to https://help.github.com/.

### Vagrant
If you want to learn more about Vagrant or configure your Vagrant box, head over to https://www.vagrantup.com/docs/index.html

### Virtualbox
If you are experiencing any issues with Virtualbox, head over to https://www.virtualbox.org/wiki/Documentation
