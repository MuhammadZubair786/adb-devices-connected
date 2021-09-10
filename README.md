# adb-devices-connected
Step 1:

check adb install or no on your system 
	command : adb

step 2:

if not install adb then install 
Go to this Link : https://www.xda-developers.com/install-adb-windows-macos-linux/
Then For Window : Scroll Down This Page (How to setup ADB on Microsoft Windows)

step 3:

Extract This Folder 
Then Add Path Of Extract Folder Platform In Advance Enviromental Variable  >System Variable >Path >Edit>New >Paste path:

Step 4 :

Again check adb install or no on your system 
	command : adb

step 5:

PC Connect Mobile With Data Cabel

step 6 :
Run This Command :
	command : adb tcpip 5555

Step 7 :
	
And Then Check Your Mobile Ip Address Then Paste and run this command
	command : adb connect 192.168.0.101:5555
	192.168.0.101 =>replace With Your Mobile IP Addressing

step 8 :
	adb disconnect 192.168.0.101:5555
