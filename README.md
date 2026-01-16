# Maturity Model for Microsoft 365 Agent
This repository holds the source for the Maturity Model for Microsoft 365 Agent.
This agent helps users get answers to their questions, provides support and guidance for using the Maturity Model for Microsoft 365. The Maturity Model aims to help businesses understand the benefits and impacts that they can expect as they improve their competencies in key business areas.

For more information on the [Maturity Model for Microsoft 365](https://learn.microsoft.com/microsoft-365/community).

## Installation of the Maturity Model for Microsoft 365 Agent

The agent is currently built using Microsoft Copilot Studio. To make use you will need to have access to a Microsoft 365 environment and Microsoft Teams.

### Introduction

This document explains how to install the Maturity Model for Microsoft 365 Agent solution.

### Pre-requisites
You will need:

- A copy of the Maturity Model Agent ZIP file
- Access to a Power Platform environment
- A Microsoft 365 Copilot licence (Teams or Microsoft 365 Copilot Bizchat)


### Installation
To install the Maturity Model for Microsoft 365 Agent:

- Browse to https://make.powerapps.com/
- Ensure you have selected the correct environment.

![Image displaying the url and highlighting the environment selector on the top-right.](image.png)

- Select Solutions.
![alt text](image-1.png)
- Choose Import solution.
![alt text](image-2.png)
- Click Browse and select the ZIP file:
    - MaturityModelForMicrosoft365Agent_x_x_x_x.zip
- Click Next
- Click Next again
- Check the connection
- Click Import and wait for the solution to install.

Once complete, you will see a success banner confirming installation.
![alt text](image-3.png)


#### Publishing the Agent to Microsoft 365 Copilot
Now that the solution is imported, publish the agent:

- Browse to https://copilotstudio.microsoft.com/
- Click Agents
![alt text](image-4.png)

- Select Maturity Model for M365 Agent
![alt text](image-5.png)
- At the top, click Publish
- Read the information about experimental models
![alt text](image-6.png)
- Click Publish to confirm and wait
- Once published, go to the Channels tab
![alt text](image-7.png)
- Select Teams and Microsoft 365 Copilot
- In the right-hand panel:

    - Turn on Microsoft 365 Copilot
    - Click Edit Details
![alt text](image-8.png)

- Update details:
- Short description:
    - Make a difference at your organisation with Microsoft 365 and the Maturity Model.
- Long description:
    - Use the Maturity Model for Microsoft 365 Agent to help you understand how you can position your Microsoft 365 solution with your boss, stakeholders, and make a difference in your organisation.


Icon:
Select the agent icon provided in the ZIP package.
![alt text](image-9.png)

Developer name:
Your company name

- Click Save, then Save again in the channel settings.
- Finally, click See agent in Microsoft 365.

Microsoft 365 Copilot will open and prompt you to add the agent. If you see an error, wait a few minutes for the agent to fully initialise.

![alt text](image-10.png)


## Try it out
On first run, you will be asked to set up a connection.

![alt text](image-11.png)

- Click Open connection manager
- Find Microsoft Learn Docs MCP
- Click Connect
- Click Submit

![alt text](image-12.png)

- Once connected, close the tab and return to the agent
- Click Retry

![alt text](image-13.png)

Your agent is now ready to use. 🎉
