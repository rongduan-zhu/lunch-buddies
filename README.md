# lunch-buddies
An web app that helps employee in their company to find lunch buddies and schedule lunch meet ups.

# Setup
## Windows
### Required Installations
* Docker Toolbox
### System Configuration
* Make sure virtualization is enabled
### Environment Setup
1. Open terminal and start docker machine. ```docker-machine create --driver virtualbox default```. This will create a machine named ```default```
2. SSH into the machine you just created ```docker-machine ssh default```
3. Install [My Boot2Docker](https://github.com/wharsojo/myboot2docker)
4. (Optional) Your host drives are mounted into the machine. You can access C drive like ```/c/```. You can configure machine to go into a directory when you ssh into it. To do so, please do ```echo 'cd /boot/to/this/directory' >> ~/.zshrc```. And then logout and ssh back in.
### Running Docker Containers
Everytime you want to run docker related commands, just run step two in __Environment Setup__.
