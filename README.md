# Whatsapp-Linux
It is not an official application of WhatsApp Inc. Build your own custom client for WhatsApp.  Unfortunately there is no official Whatsapp client for Linux operating systems. But we are a Linux users, if it is not exists, we will create it.  This is created with latest version of Electron v8


![whatsapp1](https://user-images.githubusercontent.com/92087997/148071783-7cddb3ea-80ac-40e7-9326-a5735de4d336.png)



# How to use
Clone and run this repository you'll need Git and Node.js (which comes with npm) installed on your computer. From your command line:

# Clone this repository
git clone https://github.com/AnroKruger/Whatsapp-Linux.git
# Go into the repository
cd wazapp
# Install dependencies
npm install
# Run the app
npm start
Create linux executable file
# Create package for linux 64bit
npm run build-linux64
# Create package for linux 32bit
npm run build-linux32

This command will create a folder called Wazapp-linux32(64) that contains the executable file. Now you have to include this file as a startup application of your Linux operating system

# NOTE
If it is not already installed, you have to include electron-packager for creating the linux executable file with the following command:

# install the dependency 
npm install electron-packager
