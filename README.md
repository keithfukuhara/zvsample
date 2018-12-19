# zvsample
Demonstration Web Application for ZeroDown Software / ZeroNines Technology Partners for Azure Stack

The tar file is too big for GitHub.  To download the package, issue the following command from the Ubuntu Server

Environment:
- Ubnuntu 16.04 LTS Operating System
- Internet Access

Download the zvsample-ASDK-build.tar.gz file

wget http://downloads.zerodownsoftware.com/zvsampled/zvsample-ASDK-build.tar.gz

Unpack the file:  

tar xvzf zvsample-ASDK-build.tar.gz

Run the Installation Script

./install.sh


The Installation Script installs the zvsample application into the Ubuntu Server.  To start and stop the services,
the command:
zvsample {start | stop | restart | status}

Application is accessed via port 8080, therefore, port 8080 needs to be opened to this deployment.
