# Ancora-Education-Ucertify-Lab16
# Setting Up a VPN Server with Windows Server 2016

> **Original Lab Source**
> This lab was available through:
[https://ancoraeducation.ucertify.com/app/func=navigate_items&item_sequence=7]

## Objective of the Lab
In this lab, you will learn to set up a VPN server with Windows Server 2016.

A VPN server is a type of server that enables the hosting and delivery of VPN services. It is a combination of VPN hardware and software technologies that provides the VPN clients with the connectivity to a secure private network, or the VPN.

## Instructions
### STEP 1
Click the Start menu and open Server Manager.

### STEP 2
In the Server Manager window, in the right pane, click Add roles and features.

### STEP 3
In the Add Roles and Features Wizard window, perform the following steps: 

a. At the Before you begin step, click Next thrice.

b. At the Select server roles step, under Roles, check the Remote Access checkbox and click Next thrice.

c. At the Select role services step, check the DirectAccess and VPN (RAS) checkbox and at the Add Roles and Features Wizard prompt, click Add Features and click Next thrice. 

d. At the Confirm installation selections step, click Install

**CAUTION**
The installation process may take approx 5-10 minutes.

e. At the Installation progress step, click the Open the Getting Started Wizard link

### STEP 4
In the Configure Remote Access window, perform the following steps: 

a. At the Configure Remote Access step, click Deploy both DirectAccess and VPN (recommended).

b. At the Remote Access Server Setup step, verify that the Behind an edge device (with a single network adapter) radio button is selected and uCertify.ucertify.livelabs is typed in the Type the public name or IPv4 address used by clients to connect to the Remote Access server text box, and click Next.

c. At the Configure Remote Access step, click Finish. 

d. Wait for 1-2 minutes for the configuration to be done successfully. 

**Caution**

Ignore any warning message.

e. At the Applying Getting Started Wizard Settings prompt, click Close. 

**Caution** 

If you observe any error, click Reload. 

f. You will observe the Remote Access Management Console window. 

**Caution**

Click the Refresh button if you don't see the configuration. You may need to scroll horizontally to see the Refresh button and the Close button.

## Disclaimer

This repository is for **educational and personal learning purposes only**.  

The original lab content belongs to **uCertify / Ancora Education** and remains their copyrighted material.  
This repository is not affiliated with, endorsed by, or sponsored by uCertify or Ancora Education.  

No copyright infringement is intended.  
Use of any tools or techniques mentioned here should only be performed in authorized, legal environments.
