# IN A NUTSHELL
## I will explain the concepts in my words about this project which is very xciting!

### **¿What is a zero-day?**
Day zero is known in computing as a software vulnerability and is called "day zero" because it is when a hacker was able to obtain software earlier from its first release, which was obtained by stealing the information from a developer's computer.
funte: [DiaZero-Wikipedia](https://en.wikipedia.org/wiki/Zero-day_(computing)).

### **Virtual machine!**
vitual machine is an emulation of OS or operating system, it is the opportunity that you have one operating system within another! the most popular is [Virtual Box](https://www.virtualbox.org/wiki/Downloads) who operates on this occasion with Linux ubuntu! to continue our studies!


## **Using Vagrant on your personal computer**
### Do not worry! I know it's scary but together we did it !!
  - let's download [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
    - let's download [Vagrant](https://www.vagrantup.com/downloads.html)
      - I also recommend you download [powershell](https://docs.microsoft.com/en-us/powershell/scripting/windows-powershell/install/installing-windows-powershell?view=powershell-7)
        - and we run everything! it's just giving next, next!

	When you finish installing everything you are ready to start! vagrant and everything it takes to complete this project!

	### **Recuerda es para Windows 10**
	#### write the same as me!
	**It is a bit late, be patient XD**
	with this command we add the virtual machine
	```sh
	$ vagrant box add ubuntu/trusty64
	```
	Now we start vagrant
	```sh
	$ vagrant init ubuntu/trusty64
	```
	Now we will start the Virtual Machine
	```sh
	$ vagrant up
	```
	by last
	```sh
	$ vagrant ssh
	```

	### **Now you only see the powershell blue screen right? but with something that will make your heart happy !! you will see the next line!**

	```sh
	$ vagrant@vagrant-ubuntu-trusty-64:
	```
	### **And you're already working with VM and Vagrant**
	#No se desanimen! que si otros pudieron tambien nosostros podemos hacerlo!#
