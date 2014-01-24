# Welcome to the docs! 





## How to get started 

This is the guide to help you get started with Vagrant, Boxes and all these magic stuff. 

### Requirements:
- You need the VagrantFile
- You need the Cheffile
- You need to .gitignore the local ./cookbooks on your repo



### Next: install plugins and Vagrant itself 
1. Install Vagrant file for your OS: http://www.vagrantup.com/downloads.html

2. You'll need to install a specific Vagrant plugin named 
    `vagrant-librarian-chef`, here is how to do it:
    ```
      vagrant plugin install vagrant-librarian-chef
    ```
    Vagrant has its own ruby core already installed, 
    so don't worry about librarian-chef being written in ruby.


3. After that, run `vagrant up` and cookbooks will be installed automatically.
