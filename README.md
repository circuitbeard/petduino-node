# node-red-contrib-petduino

A set of <a href="http://nodered.org" target="_new">Node-RED</a> nodes for interacting with a <a href="http://circuitbeard.co.uk/petduino" target="_new">Petduino</a>.

## Install

Run the following command in the root directory of your Node-RED install

    npm install node-red-contrib-petduino


## Usage

### pet-event

A node that listens to a serial connection for a specified Petduino event, parsing out any associated value.

![](assets/screenshot01_01.png) 

***Caption:** pet-event settings dialog*


![](assets/screenshot01.png)

***Caption:** example of correct wiring of the pet-event node to an incoming serial node*

### pet-action

A node to construct a Petduino serial command of the specified action type with the specified value payload.

![](assets/screenshot02_01.png)

***Caption:** pet-action settings dialog defining a state change action*

![](assets/screenshot02_02.png)

***Caption:** pet-action settings dialog defining a screen layout to draw to the Petduino screen*

![](assets/screenshot02.png)

***Caption:** example of correct wiring of the pet-action node to an outgoing serial node*