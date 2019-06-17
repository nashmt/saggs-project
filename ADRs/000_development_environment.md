# Choice of Dev Environment
# Status: accepted
# Context
We need a development environment in which it is easy to collaborate, install packages,
and update as required.
# Decision
We will run a CentOS 7 Linux instance using AWS through SAGGS DivvyCloud account.
The instance is titled Matt's Web Dev, or something similar.
The primary user is centos and SSH requires a PPK to authenticate.
# Result
This Linux instance will allow us to install all required software from the command line,
and should be able to instantiate and run quickly amongst all platforms. 
