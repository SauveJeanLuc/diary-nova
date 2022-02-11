**- What is Docker ?**

Docker is a platform for building, running and shipping applications.

Sometimes, The App may only work on your Machine:

Bcz:
* One or more files missing
* Software Version mismatch
* Different Configuration Settings

This is where Docker comes in Rescue.

**- Virtual Machines Vs Containers**

How are containers different from Virtual Machines?

_Virtual Machine:_
- An abstraction of a machine (physical hardware)
Example: Mac may run Windows & Linux using Hypervisors E.g: VirtualBox, VMware or Hyper-v(windows only)
 Problems of VM:
* Each VM needs a full-blown OS
* Slow to start
* Resource intensive

_Container:_
- An isolated environment for running an application.
Benefits:
* Are lightweight
* Use OS of the host
* Start quicly
* Need less hardware resources

**- Architecture of Docker**

It uses a Client - Server(Docker Engine) Architecture.
Client communicates to server via REST API.

Container is a just a process as all others, sharing the kernel of the OS.

**- Installing Docker**

Follow these Tutorials from Digital Ocean: 
https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-ubuntu-20-04

**- Development Workflow**

To run App using Docker,
Take any App and Dockerise it by adding a Dockerfile to it.

Docker will then Package the app into 
