# flow3-Node-RED
This repository contains the third excercise of Node-RED for the course of Internet of Things of Código IoT

# Introduction
This excercise connects an Inject node to a Function node to a Text (dashboard) & Debug node to generate a TimeStamp every one second with the following format: "Day Month Date Year Hour:Minute:Second TimeZone" in a new tab, open with http://localhost:1880/ui

# Material
To make this flow (program) you need:
* Computer
* [Ubuntu](https://releases.ubuntu.com/20.04/)
* [NodeJS](https://nodejs.org/es/)
* [NPM](https://www.npmjs.com/)
* [Node-RED](https://nodered.org/docs/getting-started/local)

# References
* [Node-RED Page](https://nodered.org/)
* [Running Node-RED locally](https://nodered.org/docs/getting-started/local)

# Instructions

### Previous requirements 
Run the following commands in a terminal to install Node.js LTS (v16.x):
* sudo apt install curl
* curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
* sudo apt-get install -y nodejs
Install build tools
* sudo apt-get install -y build-essential
Install de Node-RED
* sudo npm install -g --unsafe-perm node-red

### Environment preparation
Open Node-RED
* Open a terminal (DON NOT CLOSE, ONLY IF YOUARE DONE USING NODE-RED) and write: node-red
* Open a window in your web browser and write: localhost:1880

### Process
* Drag a Inject, Function, text and a Debug node to the Flow 3 page
* Connect nodes in the above order, Funtion to both text and Debug node (view the following image)

![image](https://user-images.githubusercontent.com/83924529/187830926-ec849582-4911-4a77-83c2-7a04c4ce2f8a.png)

* Doube clic the timestamp node and make the following configuration

![image](https://user-images.githubusercontent.com/83924529/187826036-c397f678-3caf-4dbf-af4f-0e52c1651f54.png)

* Open the Dashboard tab by clicking on the down arrow

![image](https://user-images.githubusercontent.com/83924529/187831003-fbe63d3f-7a9a-4ea1-b965-0c8a5f05c596.png)

* Add a tab named flow3

![image](https://user-images.githubusercontent.com/83924529/187831137-ef9a475d-e8ef-4852-8c02-474c09ed71c0.png)

* Add a group named Date

![image](https://user-images.githubusercontent.com/83924529/187831179-15315633-74ba-4a26-8026-a2f01a48e326.png)

* Double clic on the text node and make sure to select the group we just created, you can also add a label

![image](https://user-images.githubusercontent.com/83924529/187831311-c6dd46f3-43fb-4fcd-a3fd-42aee138a310.png)

* Deploy the program
* Debug
* Open a new tab and write "http://localhost:1880/ui" or clic on this icon

![image](https://user-images.githubusercontent.com/83924529/187830754-870bdfde-d91b-4ad5-abec-fb33859e6c0f.png)

# Results
The following image shows the results for flow1 in Node-RED

![image](https://user-images.githubusercontent.com/83924529/187830810-d801c4b6-3991-41e3-a038-644657131dd9.png)

# Evidence
The evidence is found in the flow3.json file, uploded in this repository

# Credits
Flow developed by Amy Malavar
* [GitHub](https://github.com/amymalavar)
* [LinkedIn](https://www.linkedin.com/in/amy-malavar)
