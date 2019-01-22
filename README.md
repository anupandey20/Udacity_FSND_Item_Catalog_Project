**Item Catalog Project**

Udacity Full stack web developer nanodegree project 

**Project Overview**
To develop a web application that provides a list of items within a variety of categories and integrate third party user registration and authentication
Authenticated users will have the ability to post, edit, and delete their own items

**How to execute**
Pre-requisites
- Python 2.7
- Vagrant
- VirtualBox

**Set up and execution of Project**
- Install Vagrant and VirtualBox
- Download or clone https://github.com/udacity/fullstack-nanodegree-vm repository
- Find catalog folder and replace it with the content of this current repository, by downloading or cloning it from here.
- Navigate to /vagrant/catalog sub-directory
- Type vagrant up in the terminal
- Connect to the VM by below command: vagrant ssh
- Type cd /vagrant 
- Type cd catalog
- Execute python database_setup.py to set up the database
- Execute python catalogCategories.py to insert dummy values in database
- Run this application: python application.py
- Open http://localhost:8000/ locally and check the application



