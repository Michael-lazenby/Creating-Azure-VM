# Creating-Azure-VM

<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Creating Azure virtual machines</h1>
<br />



<h2>Requirements</h2>

- Microsoft Azure(You can use the free version a debit/credit are required to sign up)
- Intnernet connection

<h2>High-Level Steps</h2>

- Select "Virtual Machine" in the Azure portal and then select "create Azure virtual machine"
- Fill in the required fields on the basics tab
- Click "Review + create"
- Click "Create" after the validation process
- View Newely created VM in Network Watcher
- Delete resource group to save credits after use
<h1>Lab Summary</h1>
<h2>Creating a virtual machine</h2>
<p>
The first step of this project was to create your first virtual machine. I did this by selecting "virtual machine" on the azure dashboard and then clicking create, another way to do this is by using the search bar and typing in "virtual machine" after that you can click on it and select "create"</p>
<img src="https://i.imgur.com/YK94SIh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Filling out the basic information</h2>
<p>
After clicking "create virtual machine" I was redirected to the "basics" page, and this is the page where I filled out the information for my virtual machine. On this page I decided if I wanted to create a new resource group or add my virtual machine to an existing resource group. I also choose a region that was closet to me but I also noticed that not every service is avaliable in every resource group. After selecting the region I created a username and password for my virtual machine. After I filled all the required fields out I clicked "Review + create". After clicking "Review + create" I had to make sure the virtual machine passed the validation, and once it passed the review I was able to officially create my virtual machine.
</p>
<br />

<p>
<img src="https://i.imgur.com/SDL7FsW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<h2>Virtual machine overview</h2>
<p>
When a virtual machine is created in azure it also creates a virtual network, a virtual NIC, and a Network Security Group. Once the virtual machine was set up I was able to view the VMs general information under the "Overviw" tab. The information in this tab is important for things like RDP and SSH.  </p>
<img src="https://i.imgur.com/vbtVvOi.png" width="80%" alt="Disk Sanitization Steps"/>
<br />


<br />
<h2>Conclusion</h2>
<p>This was a brief overview on how I created a virtual machine, and there are so many other things that can be configured to personalize the VM. If you would like to follow this guide please remember once you are done with a virtaul machine delete it because you will lose azure credit. The price of the virtaul machine is determined by the features you are needing for your particular setup. </p>
