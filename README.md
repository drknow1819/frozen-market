
# Project 4: _**Item Catalog**_

The Item Catalog project consists of a web application ***"Frozen Market"***  using the Python framework Flask that provides a list of items within a variety of categories, as well as provide a google registration and authentication system..

## The database
**Frozen Market** database has lots of information, it includes three tables:
* **User** - Which contains all information from the signed in users and the creators
of items and categories in the market.
* **Category** - Has data about categories names, brief description of each category
and creator's id.
* **Item** - Includes items names, each item nutrients, price, weight
and thier related ids in the category and user tables.


## Usage
To run this app, you'll need database software(provided by a Linux virtual machine)
and the **Frozen Market** database. **Don't worry** all links supported below.
#### Terminal
_"If you are using a Mac or Linux system, your regular terminal program will do just fine.
On Windows, recommended to use the Git Bash terminal that comes with the Git software.
If you don't already have Git installed, download Git from [git-scm.com](https://git-scm.com/downloads)."_
#### Download and Install Virtual Machine
I recommend using tools called [Vagrant](https://www.vagrantup.com/) and [VirtualBox](https://www.virtualbox.org/wiki/Downloads) to install and manage the VM.

*** _**Ubuntu users:** 
If you are running Ubuntu 14.04, install VirtualBox using the Ubuntu
Software Center instead. Due to a reported bug, installing VirtualBox
from the site may uninstall other software you need._

**VirtualBox** is the software that actually runs the virtual machine.
Install the platform package for your operating system.
You do not need the extension pack or the SDK.
You do not need to launch VirtualBoxafter installing it; Vagrant will do that.

**Vagrant** is the software that configures the VM and lets you share
files between your host computer and the VM's filesystem.

*** **_Windows users:_** 
The Installer may ask you to grant network permissions to Vagrant or make
a firewall exception. Be sure to allow this.
#### Configure your VM
First create a folder in your desired directory and from your terminal `cd`
into this folder. For example, I've created a folder titled **frozenmarket** on my
desktop.

I executed the following command in Terminal to `cd` to my folder:
```
$ cd ~/desktop/frozenmarket
```
To start configuring **vagrant** paste the following command in your terminal.
```
vagrant init bento/ubuntu-16.10 \  --box-version 2.3.5
```
**Note:** If you are using Windows OS excute the following commad insted of
the previous one.
```
vagrant init bento/ubuntu-16.04-i386 \  --box-version 201812.27.0
```
You can access all the other [Boxes](https://app.vagrantup.com/bento) if you want to install diffrent environment.

* **Congratulation ... You have created "VAGRANTFILE"**


#### Start the virtual machine
After you created **vagrantfile** in the previous step, now run the command `vagrant up`.
This will cause Vagrant to download the Linux operating system and install it.
This may take quite a while (many minutes) depending on how fast your Internet connection is.

When `vagrant up` is finished running, you will get your shell prompt back.
At this point, you can run `vagrant ssh` to login to your newly installed Linux VM!

#### Running the app
You can use Github to fork and clone the repository [https://github.com/drknow1819/frozen-market.git](https://github.com/drknow1819/logs_analysis_project.git) to the directory
(_ex:_**frozenmarket**) early created.

#### Running the code
Now `cd` into the directory containig the app.
Your terminal shoud look like this:
```
vagrant@vagrant:/vagrant/frozenmarket-master$
````
To lunch the program paste the below command in your terminal then hit **enter** kye :
```
python frozen.py
```

After running the program you will be able to access and test the application by visiting  [http://localhost:5000](http://localhost:8000/)  locally.







## Techniques

Although it's a simple `code` but it includes alot of techniques,
let me mention some of them:

- RESTful API
- python
- Flask framework
- Third-party OAuth authentication ***"google"***
- Various HTTP methods
- CRUD (create, read, update and delete) operations.) function


## Usefull Links

- [Flask: Documentation](http://flask.pocoo.org/docs/1.0/)
- [Flask Tutorial](http://flask.pocoo.org/docs/1.0/tutorial/)
- [Stack Overflow](https://stackoverflow.com/)
- [W3Schools](https://www.w3schools.com/)
- [Tutorialspoint](https://www.tutorialspoint.com/)

