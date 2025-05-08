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

<p>

<img src="https://github.com/user-attachments/assets/311f1cf4-f770-45a5-aba7-960268113dfa" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
</p>


</p>
<br />

<p>
Create a text file on your local desktop.
  
<img src="https://github.com/user-attachments/assets/2e504d87-6259-4f53-806c-0e799e0723d5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/c8f196f4-3f76-4aa7-ac4c-6ff63f83f096" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>
<p>
  
Create a Container within your Storage Account and upload the text file you created to the Azure Storage Account.

<img src="https://github.com/user-attachments/assets/beb81741-3fd4-40d3-9834-b5fa897d2f76" height="80%" width="80%" alt="Disk Sanitization Steps"/>  

</p>
</br>

<p>

Edit the file within the Storage Account (For example, I added the word "Goodbye"), then download the file.
  
<img src="https://github.com/user-attachments/assets/bee9e0e8-12a8-4088-a7a1-530139df3a3a" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/70fd1f29-b9fd-41e1-ba6b-5106ff1891c0" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>

<p>
Open the file and observe the changes.

<img src="https://github.com/user-attachments/assets/f9b6cb13-49ac-401b-b4d4-166ab382cdf9" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>

<p>
  
Finally, delete the Resource Group created in step 4 (to ensure you don’t incur “cost”) & verify that the Resource Group has been deleted.

<img src="https://github.com/user-attachments/assets/d98d6c40-97df-4f1c-a130-82f70b4a6aa7" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
</br>
