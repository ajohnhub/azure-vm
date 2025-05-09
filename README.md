![image](https://user-images.githubusercontent.com/109401839/230745596-57cee9bd-687c-427d-b0db-d1080df77f7e.png)


<h1>Creating Virtual Machines</h1>
This walkthrough demonstrates how to create Virtual Machines within the Microsoft Azure Portal.
</br>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2> 

- Windows 10 (22H2)


<h2>Walkthrough Steps</h2>

<p>
Create a Resource Group.
  
<img src="https://github.com/user-attachments/assets/9fa54e2c-f7da-4fef-b0d0-e9f9304f9aae"
height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<br/>

<p>
Create a Windows 10 Virtual Machine (VM).
While creating the VM, select the previously created Resource Group.


<img src="https://github.com/user-attachments/assets/7c9e69cc-82fc-45cd-b8b4-d08f3f96f349" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<br>
</br>


<p> 
For Image, select Windows 10 Pro, version 22H2.
For Size, select Standard_d2ls_v5 (2 vcpus)
</p>

<img src="https://github.com/user-attachments/assets/eb74c264-a599-47ef-a6ee-e0ec1c08caaf" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/7321dfb2-873a-4149-a0d8-e9fa556df2e0" height="80%" width="80%" alt="Disk Sanitization Steps"/>

    
</p>
<br>
</br>

<p>While creating the VM, allow it to create a new Virtual Network (VNet).

<img src="https://github.com/user-attachments/assets/1f706119-05ed-4219-82e1-88a6d06b6498" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>

<p> Check the licensing box and create the Virtual Machine.

<img src="https://github.com/user-attachments/assets/68268649-a9b6-434d-82e0-9c25f633e9f2" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/edff4163-da56-4f1d-a957-1d054e7fe9fb" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>


<p>Create a Linux (Ubuntu) VM. 
Make sure to select the previously created Resource Group and Virtual Network.

<img src="https://github.com/user-attachments/assets/623feb52-0e79-4ef8-8ca2-71566aee9f9e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
</br>

<p> Choose Ubuntu Server 22 as the Image and the same Size as the Windows VM.
<img src="https://github.com/user-attachments/assets/fabe4839-3c53-434f-8602-2ac2a6434b7e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/5f9f069e-d2de-420c-b1ce-e553b34f3cdc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
</p>
</br>

<p>
Make sure the Virtual Network IS THE SAME. Then, review & create the Linux VM.

  
<img src="https://github.com/user-attachments/assets/7a43c9e9-b5d2-4c50-a70a-f4fbe252de54" height="80%" width="80%" alt="Disk Sanitization Steps"/>


</p> 
</br>

