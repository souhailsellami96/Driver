# Labforward device and driver communication
The main purpose of this project is to asynchronously emulate IoT device communication  

## Development time taken for the project:
  * 35 minutes for Brainstorming
  * 1.5 hour for Developement
# Pre-reqs
To build and run this app locally you will need a few things:

  * Install [Node.js](https://nodejs.org/en/download/current/)
  * Install [VS Code](https://code.visualstudio.com/Download)
  * MQTT Broker [Mosquitto](https://test.mosquitto.org/)

# Getting started
## Clone the repository
 git clone  https://github.com/souhailsellami96/Driver.git
## Install dependencies
 ### cd <project_name>
 ` npm install `
 ### Link It Globally
 ` npm link `
 ### configure .env file 
``` Javascript
# Configure your env file
 intMQUsername=''

 intMQPassword=''

 intMQClientId=''

 intMQHost='mqtt://test.mosquitto.org'

 intMQPort=1883
```
# Run the project
npm start 
### Labforward CLI:
 `Usage: labforward [global options] command

Options:
  -v, --vers           output the current version
  -h, --help           display help for command

Commands:
  send|s <param_name>  Read a paramter value
  restart|rs           Restart device
  error|e              Read latest error code
  help [command]       display help for command


Function                       Alias        Description

version                        -v           To check the version of the labforward cli
labforward send <param_name>   s            To read current value  for a parameter from 
                                            device  eg : Temperature-F , Temperature-C, Humidity
labforward restart             rs           To initate device retart
labforward  error               e           To get latest error code
 `
# Why testing ?
Testing allows us to refactor,maintain and expect alias.


# Deploying the app
There are many ways to deploy an Node app and almost nothing changes.
