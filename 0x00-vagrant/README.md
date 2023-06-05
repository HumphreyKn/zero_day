# How I installed Vagrant on my personal computer:
*I'm on Ubuntu 23.04 (Lunar Lobster)*

- Open the Terminal:
	- Now you will the command line in your Terminal (each of them start with `$`)
- Install the VirtualBox: `$ sudo apt-get install virtualbox`
- Install Vagrant: `$ sudo apt-get install vagrant`
- Add the **Ubuntu 20.04 (Focal)** image to your box list: `vagrant box add ubuntu/focal64`. **Warning: This step can take time.**
- Create your first virtual machine:
	- `$ vagrant init ubuntu/focal64` ->It will generate a Vagrantfile with `base = "ubuntu/focal64"`-*you don't have to execute this command line everyday, only once, to create a virtual machine*
	- `$ vagrant up` -> It will start your virtual machine
	- `$ vagrant ssh` -> Now you are inside your virtual machine.
	- `$ exit` -> When you are done, you can exit the virtual machine

**Source:** ALX Software Engineering Intranet
