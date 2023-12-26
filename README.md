# Palo Alto Networks - XSOAR
This repository contains helpfull custom **integrations** and **automations** that I personally developed or extended base XSOAR capabilities that can be applied universally in xsoar.
Hopefully you will find something useful here that can help or speed up your goal. 😃

**Note**: I will be adding further things as I see fit, so make sure to keep an eye out

## Integrations
In order to use these integration in Palo Alto Networks XSOAR, simply download the .yml file and upload it in the XSOAR integrations page.
Happy enginnering 🎃

#### 1. OneTrust
I developed this integration in order to better utilize the OneTrust APIs within XSOAR for risk assessement intake as an incident. This was part of a migration from excel supported CyberRisk process to XSOAR.
This integration is working with the following APIs:
- Get Assessment List
- Get Assessment Details
- Send Back Assessment Under Review to In Progress
- Update Assessment Tags(In development)
