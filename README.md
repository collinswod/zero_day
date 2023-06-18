# VAGRANT README

This is the README file to setup virtualization using VAGRANT on the local machine.


## PURPOSE OF THE INSTALLATION

- VAGRANT INSTALLATION
- UBUNTU_20.04 INSTALLATION

## INSTALLATION PROCESS FOR VAGRANT AND UBUNTU20.04

 - Download and install vagrant using this link https://developer.hashicorp.com/vagrant/downloads
 - Choose a base box: A base box is a pre-configured virtual machine image that serves as the foundation for your Vagrant environment. You can search for available base boxes on the Vagrant Cloud (https://app.vagrantup.com/boxes/search) or create your own. Once you choose a base box, note down its name or URL.
i
 - Create a project directory: Create a new directory for your Vagrant project. This directory will hold your Vagrantfile and any additional project files.

 - Initialize the Vagrant environment: Open a terminal or command prompt, navigate to your project directory, and run the following command: vagrant init <base_box_name>. This command creates a new Vagrantfile in your project directory.

 - Start the Vagrant environment by running this command : vagrant up
This command downloads the base box (if it's not already downloaded) and starts the virtual machine

 - To access the virtual machine, type : vagrant ssh. This will open an SSH session to the virtual machine, allowing you to interact with vagrantbox in our case Ubuntu20.04.



















