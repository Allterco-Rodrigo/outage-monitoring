# outage-monitoring
Node Application and Shelly Script to communicate between at least 2 plugs. One behind a UPS unit.

# Instalation instruction
Copy the script file to a shelly product behind a UPS unit

# Edit these parameters accordingly inside the script

// email of the person receiving the notification

let email      = 'demonstration@allterco.com';

// IP list of all devices that will be monitored

let targetIp   = ['192.168.15.35'];

// number in seconds that will take to check each device in the list

let loopTime   = 60*60*12 ;

// send emails even when the device is connected

let opt = false;

// email server configuration. Two options. Comment the line that won't be used

// 1) ip address of the computer that will run the email server locally

// let computerIp = '192.168.15.99';

// 2) Shelly public ip address of our server that is running the email server via internet

let computerIp = '23.115.145.128';

# Save and run the script
