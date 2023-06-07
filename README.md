# Creating-Azure-VM

<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Creating Azure virtual machines</h1>
In this project I created a virtual machine in azure and tinkered<br />



<h2>Requirements</h2>

- Microsoft Azure(You can use the free version a debit/credit are required to sign up)
- Intnernet connection
- Various Command-Line Tools
- Various Network Protocols (SSH, RDP, DNS, ICMP)
- Wireshark (Protocol Analyzer)

<h2>High-Level Steps</h2>

- Select "Virtual Machine" in the Azure portal and then select "create Azure virtual machine"
- Fill in the required fields on the basics tab
- Click "Review + Create"
- Click "Create" after the validation process
- View Newely created VM in Network Watcher
- Delete resource group to save credits after use
<h1>Lab Summary</h1>
<h2>Creating virtual machines</h2>
<p>
The first step of this project was to create your first virtual machine. I did this by selecting "virtual machine" on the azure dashboard and then clicking create, another way to do this is by using the search bar and typing in "virtual machine" after that you can click on it and select "create"</p>
<img src="https://i.imgur.com/YK94SIh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<br />

<h2>Wireshark installation and observation</h2>
<p>
Before I started the lab I installed Wireshark. I observed network traffic with Wireshark, and I was also able to filter ports by using the filter bar. For example, I filtered ICMP(Internet Control Message Protocol) and viewed traffic between my virtual machines when I sent ping requests to the Ubuntu VM. After sending one ping request I sent a continuous ping request to the Ubuntu VM.
</p>
<br />

<p>
<img src="https://i.imgur.com/SDL7FsW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
<h2>Blocking inbound ports with port security rules</h2>
<p>
The next step of my project was to stop the continuous ping requests from my Windows VM. I did this by adjusting the inbound port rules for my Ubuntu VM via the Network Security Group settings, and I denied traffic from the ICMP port. This allowed me to observe the ping requests timing out, and I didn't receive a response from the VM. </p>
<img src="https://i.imgur.com/vbtVvOi.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<h2>Other port practice</h2>
<h3>Connecting with SSH</h3>
<p>
I connected to the Ubuntu VM using SSH. While connected to the Ubuntu VM I created a new directory using the mkdir command and added a file to the directory using the touch command. 
<img src="https://i.imgur.com/4RHnH8G.png" width="80%" alt="Disk Sanitization Steps"/>
<h3>DNS traffic monitoring</h3>
<p>
I used nslookup to send a DNS request to Google. Google's DNS server responded with IPv6 and IPv4 addresses .</p>
<img src="https://i.imgur.com/UB7QZNv.png" width="80%" alt="dns"/>

<br />
<h2>Alternative method to filter ports via Wireshark</h2>
<p>
I also learned a different method to filter ports in Wireshark. The other way to filter ports is by typing the network protocol and the port you are trying to filter. I have listed examples below:</p>

- tcp.port == 22
- udp.port == 53

<br />
<h2>Conclusion</h2>
<p> Overall this lab was insightful because it allowed me to visualize network traffic through different protocols. It allowed me to tinker with different settings and gain hands-on experience. It is important to read how network protocols work, but the hands-on experience reinforces the concepts I have been learning about. </p>
