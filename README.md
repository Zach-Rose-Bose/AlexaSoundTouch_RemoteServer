# An Experimental Alexa Skill for SoundTouch - Remote Server Component
## Overview
This repository contains one of the three components necessary enable Alexa to control Bose SoundTouch speakers. The other two required components are:
+ [AlexaSoundTouch\_AlexaSkill](https://github.com/zwrose/AlexaSoundTouch_AlexaSkill) 
+ [AlexaSoundTouch\_LocalServer](https://github.com/zwrose/AlexaSoundTouch_LocalServer) 

This Remote Server Component serves as a bridge between the AlexaSoundTouch\_AlexaSkill and AlexaSoundTouch\_LocalServer to avoid the need for port-forwarding or other custom firewall modifications.

## Setup
This should be the first of the three components that is set up. It is assumed that this component will be set up on an internet-accessible server instance.

1. Run
    `git clone https://github.com/zwrose/AlexaSoundTouch\_RemoteServer.git`
2. Enter the newly cloned directory and run
    `sudo npm install`
3. Run
    `sudo node .`

Then proceed to [AlexaSoundTouch\_AlexaSkill](https://github.com/zwrose/AlexaSoundTouch_AlexaSkill) setup.