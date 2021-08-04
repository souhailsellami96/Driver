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
 cd <project_name>
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

 `Commands:` 
   * labforward s Temperature-F : provides current temp in Fahrenheit
   * labforward s Temperature-C: provides current temp in Celcius
   * labforward s Humidity : provides Humidity
 
 
# Why testing ?
Testing allows us to refactor,maintain and expect alias.


# Deploying the app
There are many ways to deploy an Node app and almost nothing changes.
