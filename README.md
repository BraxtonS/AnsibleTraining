# AnsibleTraining
Displaying my varying knowledge of the open-source software Ansible. 


<h2>Description</h2>
So after doing some searching for new products to do some training on, I landed on gettting acquainted with Ansible. I've heard about it vaguely in the past and have seen colleagues use it while I was a SE intern at different tech companies so I deemed it the perfect tool to get a hold of and play around with. I'll plan to add more portions as I train more. This first portion covers me setting up VMs in a cloud service provider Linode, adding the VMs to the ansible inventory, running simple Ansible ad-hoc commmands, and finally using a YAML file to act as a playbook.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Ansible</b> 
- <b>Linode VMs</b>
- <b>Linux</b>
- <b>YAML</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)


<h2>Lab Screenshots</h2>

<p align="center">
Successfully made account on Linode in order to establish and make VMs: <br/> <br />
<img src="https://i.imgur.com/G6RQdPU.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
Finding a public stackscript to deploy a preconfigured VM with a script: <br/> <br />
<img src="https://i.imgur.com/Fnfw5IP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Deployed 3 VMs with one being from a stackcript and the subsequent others being made by hand: <br/> <br />
<img src="https://i.imgur.com/dzOnmIy.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
Logged into stackcript VM along with checking if Ansible is installed and configured: <br/> <br />
<img src="https://i.imgur.com/yjOTNSV.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
After this, I edited the hosts file(using vi) to add the other VMs under the group 'Linux': <br/> <br />
<img src="https://i.imgur.com/CwTWeUK.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
My first ad-hoc (denoted by the '-a') command simply pings the hosts under the Linux group that I defined: <br/> <br />
<img src="https://i.imgur.com/XO0Dq2m.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
Now I attempted to remediate these as best I could, which began with deleting Firefox from the VM: <br/> <br />
<img src="https://i.imgur.com/v4PVgGb.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
The next simple step was running Windows update on the VM repeatedly until up to date: <br/> <br />
<img src="https://i.imgur.com/hH5FBjs.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
I then ran a final credentialed scan to see the results of the remediation: <br/> <br />
<img src="https://i.imgur.com/fRRMuJ5.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br />
Here are all the scans put together: <br/> <br />
<img src="https://i.imgur.com/ggVZu8Y.png" height="80%" width="80%" alt="Lab Screenshots"/>
<br />
<br /> 
</p>
