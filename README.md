# BasicRouterSecurityConfiguration 1
This lab demonstrates how to enable a password for privledged mode on a cisco router. 









<h2>creating and accessing the router:</h2>

First we will create a router, then access the CLI interface, which we will use to configure the router. To configure said router, we must use global configuration mode. However, first we must enter privileged exec mode. which is achieved by the enable command, then configure terminal. I named the router R2 for this lab





  <br/> 
<p align="center">
<img width="1100" height="112" alt="2" src="https://github.com/user-attachments/assets/6c0f6f58-8477-4801-b163-f570f69716d9" />
<br />
<br />
<p align="center">

  
 We're now going to enable passwords, which are used to login to enable privileged exec mode on each router, and set the password to cisco. Previously we had no password set, and were able to login without any password.

<br/> 
<p align="center">
<img width="762" height="700" alt="3" src="https://github.com/user-attachments/assets/a2a348c7-993c-4ab4-8255-eb62aaab2f21" />
<br />
<br />
<p align="center">
  
We'll now view the password in the running configuration and check if it is encrypted. To do so, we use the show running-configuration command. And as we see, the password is not encrypted. 

<br/> 
<p align="center">
<img width="564" height="649" alt="4" src="https://github.com/user-attachments/assets/ab7320a5-ffd9-4874-be81-cb79d8397a03" />
<br />
<br />
<p align="center">
  
  Let's change that. We will enable password encryption using the command service password-encryption.

<br/> 
<p align="center">
<img width="510" height="650" alt="5" src="https://github.com/user-attachments/assets/303163d8-8a09-462b-8ade-94ff438aaaaa" />
<br />
<br />
<p align="center">
  
# And that’s how you configure a Cisco router with a basic password and encryption configuration.
