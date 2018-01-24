# Nanoleaf Polyglot V2 Node Server

This Poly provides an interface between NanoLeaf Aurora and Polyglot v2 server. Support control of one Aurora Light per Node Server

#### Installation

Installation instructions
You can install it manually running

1. cd ~/.polyglot/nodeservers
2. git clone https://github.com/therealmysteryman/udi-nanoleaf-polyglot.git
3. Create a custom variable named ip -> ipaddress_of_aurora
4. Before starting for the first time Nanoleaf Node Server maker sure to have the Aurora in linking mode to generate the token. (holding the power button until the light flash) If you do have a token already then created a custom variable token -> token_string

If you want to reset the token or the ip of the nanoleaf, add a custom variable requestNewToken -> 1 To force rebuild of the cache.

#### Usage

This will create two nodes of for the Nanoleaf Controller and then one for the Aurora Light.

Supported commande are :
- Off
- On 
- Brightness
- Effet

#### Source

1. Based on the Node Server Template - https://github.com/Einstein42/udi-poly-template-python
2. Library for controlling the NanoLeaf Aurora -https://github.com/software-2/nanoleaf
