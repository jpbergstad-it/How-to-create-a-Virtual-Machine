# How-to-create-a-Virtual-Machine
HOW TO CREATE A VIRTUAL MACHINE USING WINDOWS 10 IN MICROSOFT AZURE


<p> This tutorial summarizes the steps needed to create a Virtual Machine (VM) in Microsoft Azure. With a virtual machine, you can run software, test applications, store data, connect to networks and much more. We’ll create a VM that uses Microsoft 10 (different OS platforms are available too). </p>

<p>Note: This tutorial was created in October of 2023—Microsoft may have changed the options and/or the location of the different options. Use your best judgment or seek additional resources. 
</p>
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>High-Level Overview</h2>

- Start on Azure homepage
- Select the right VM creation process
- Subscription/Resource Group
- Naming your VM
- Selecting your Image (VM Operating System)
- Select VM Size
- Creating your Account
- Licensing
- Networking options
- Finalizing your VM

<h2>VM Creation Steps</h2>

<p>
<a href="https://imgur.com/jcFOneY"><img src="https://i.imgur.com/jcFOneY.png" title="source: imgur.com" /></a></p>
<p>
1.  Navigate to the Virtual Machines page either by clicking on the  icon or using the search bar.
</p>
<br />


<p>
<a href="https://imgur.com/3O4joLI"><img src="https://i.imgur.com/3O4joLI.png" title="source: imgur.com" /></a></p>
<p>
2. Click the create button (Select Azure Virtual Machine)
</p>
<br />

<p>
<a href="https://imgur.com/s4tyQu4"><img src="https://i.imgur.com/s4tyQu4.png" title="source: imgur.com" /></a></p>
<p>
3. Once you’ve clicked the create button, the “create a virtual machine” page will appear. The “basics” tab includes subscription information, instance details, security type, image (type of OS you’d like your VM to run on, VM Architecture, size (how powerful of a machine you want, Inbound port rules, and Licensing. If you haven’t previously created a resource group, you can create one here too. 
</p>
<br />

<p>
<a href="https://imgur.com/L78FC8V"><img src="https://i.imgur.com/L78FC8V.png" title="source: imgur.com" /></a></p>
<p>
4. Start with the Subscription/Resource group. Select the Resource group  you’d like to use or create a new one.
</p>
<br />

<p>
<a href="https://imgur.com/L78FC8V"><img src="https://i.imgur.com/L78FC8V.png" title="source: imgur.com" /></a>
</p>
<p>
5. Under Instance details, name your VM (VM-1 for example) and select where you’d like it to be located. Some VM options aren’t available in every location.

</p>
<br />

<p>
<a href="https://imgur.com/AIzq1Lp"><img src="https://i.imgur.com/AIzq1Lp.png" title="source: imgur.com" /></a>
</p>
<p>
6. Select your Image (Operating system of your VM). For this tutorial, we’ll select and create a VM running Windows 10. Select Windows 10 Pro, Version 22H2 - x64 Gen 2.
</p>
<br />

<p>
<a href="https://imgur.com/AIzq1Lp"><img src="https://i.imgur.com/AIzq1Lp.png" title="source: imgur.com" /></a></p>
<p>
7. For the size, it depends on what your budget is and how fast you’d like it to be. Select the “standard_E2s_v3 - 2 cpus, 16 GiB Memory ($91.98/month). Remember to terminate your machine when not in use to avoid unnecessary charges. 
</p>
<br />

<p>
<a href="https://imgur.com/m06qNUe"><img src="https://i.imgur.com/m06qNUe.png" title="source: imgur.com" /></a>
</p>
<p>
8. Create an Administrator account (allows you to log in from Microsoft Remote Desktop Connection).
</p>
<br />

<p>
<a href="https://imgur.com/7wdNLEy"><img src="https://i.imgur.com/7wdNLEy.png" title="source: imgur.com" /></a>
</p>
<p>9. Select the licensing box. Once complete, click the “next: Disks” button (followed with next: Networking) to get to the Networking tab. By going through the tabs by clicking next, it will create a virtual network for you (an error will show if you automatically click on “Review + create”). Click “Review + create” on the networking tab.
</p>
<br />

<p>
<img src="https://imgur.com/jcFOneY" height="80%" width="80%" alt="start page"/>
</p>
<p>
10. The next page will confirm that you’d like to create a virtual machine. The validation for the VM has passed (if not, it will warn you of any errors). Review the charges and settings. If everything looks good, click the “Create” blue button at the bottom.
</p>
<br />

<p>
<img src="https://imgur.com/jcFOneY" height="80%" width="80%" alt="start page"/>
  <img src="https://imgur.com/jcFOneY" height="80%" width="80%" alt="start page"/>
</p>
<p>
11. A final window will populate and let you know when the machine is available. Please be patient—this may take a couple solid minutes. You now have a VM running Windows 10. See upcoming tutorials on how to use your VM.
</p>
<br />

