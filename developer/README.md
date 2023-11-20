# WhatsApp Bot Dev Docs

## Requirements
 * Node.js v16+
* Chrome Browser
## Installation

Required packages:
```bash
sudo apt-get install libgconf2-4

```
```bash
sudo apt-get install xorg
```
```bash
sudo apt-get install xvfb
```

Installation of chrome

```bash
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```
```bash
sudo dpkg -i google-chrome-stable_current_amd64.deb
```

```bash
sudo update-alternatives --set x-www-browser /usr/bin/google-chrome
```

Node Module Installation
```bash
npm i

//use this command in the code directory
```

## Sending data to the API

To send the data(mobile number), send a request to the link below , ending with the phone number. Also include country code in request.
```bash
http://webite.address:3000/api/receiveData?phoneNumber==numberhere
```
```bash
//Example

http://webite.address:3000/api/receiveData?phoneNumber==917024567874

//include country code in mobile number start
```
Note : the web server will be running at port 3000.