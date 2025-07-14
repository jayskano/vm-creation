<p align="center">
  <img src="https://github.com/user-attachments/assets/a60432c2-d616-46bc-a9de-e813a2a88036" width="600" />
</p>

<h1>Creating a Windows and a Linux Virtual Machine in the Cloud (Azure)</h1>
This project demonstrates how I created a Windows and a Linux Virtual Machine (VM) in Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Walkthrough</h2>
<h3> Step 1: Creating a Resource Group in Azure </h3>

<p>
<img src="https://github.com/user-attachments/assets/1d0bc412-d4d2-47f7-a6df-27eea5b853bd" width="800"/>
</p>
<p>

  - To begin the project, I selected the "Resource Groups" option on the Azure homepage to create a new resource group.

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/adae69ae-800b-49fb-a98f-d1d69ab4b54b" width="800" />
</p>
<p>

  - After clicking "Create", I was directed to the resource group setup screen
  - I named the resource group "VM-Project" and selected "(US) East US 2" as my region

</p>
<br />

<h3> Step 2: Creating a Windows VM in Azure </h3>

<p>
<img src="https://github.com/user-attachments/assets/5411d865-7bce-4628-a495-b492ff9a52f9" width="800" />
</p>
<p>

  - After creating the resource group, I navigated to the "Virtual Machines" section to begin creating my first VM for the project.
  - I selected the "VM-project" resource group and named the virtual machine "windows-vm".
  - I chose "(US) East US 2" for the region, matching the region used for the resource group.
  - I left the availability options at their default settings

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/b4cf5c26-91d1-442b-b734-3bacba01f36e" width="800" />
</p>
<p>

  - I seletced "Windows 10 Pro, version 22H2" for the operating system (OS) image.
  - I chose a size with 2 vcpus and 8 GiB memory to ensure smooth performnace for the virtual machine.

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/17b7f700-1b27-432a-aeea-753e35c89e03" width="800" />
</p>
<p>

  - I created a username and password that I will use to log into the VM using Remote Desktop Connection (RDP).

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/77be9e55-67ed-487a-b870-80a04900bcb7" width="800" />
</p>
<p>

  - I selected "Next" to continue to the "Networking" tab and renamed the default virtual network to "azureproject-vm".
  - I kept the remaining settings at their defaults and clicked "Review + create" to proceed.

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/1ac4d2b8-fe6b-466f-a598-4cc93a1441c5" width="800" />
</p>
<p>

  - In the "Review + create" tab, I reviewed all of the settings to ensure that everything was correct before selecting "Create".









