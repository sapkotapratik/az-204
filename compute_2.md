![image](https://user-images.githubusercontent.com/24469318/210261207-353523d6-7f70-4e09-9ce3-f507d08fd03b.png)

![image](https://user-images.githubusercontent.com/24469318/210261364-fe7ce83b-e769-4945-846b-8878e8c4a6fa.png)


![image](https://user-images.githubusercontent.com/24469318/210262443-a9b85947-e74d-4536-8678-4ab990c93434.png)



**az deployment create --resource-grqup <name-0f-rg> --template-file template.json --parameters parameters.json**
  
 ![image](https://user-images.githubusercontent.com/24469318/210293335-bf075cc1-fcb2-4578-a520-7b1a21104a93.png)

  ![image](https://user-images.githubusercontent.com/24469318/210293460-ded4d346-a3db-4258-9228-f50f17152f0b.png)

  ![image](https://user-images.githubusercontent.com/24469318/210293500-9cb2d48e-0896-46b2-91bb-495aa7d1e099.png)
  
  
![image](https://user-images.githubusercontent.com/24469318/210293540-24b666b2-94b9-49d5-9cf5-92d128bb267f.png)

  ![image](https://user-images.githubusercontent.com/24469318/210293779-e7b565dd-9dd0-4a74-bb29-5badd92b15ad.png)

  ![image](https://user-images.githubusercontent.com/24469318/210294027-805aba55-130b-4050-a0cc-2227ae49d745.png)

![image](https://user-images.githubusercontent.com/24469318/210294108-5a9f4875-6170-41e6-9e6f-3d0fcd7c7b5d.png)

  **  We have various actions in Azure that need to registered to be used.**
  
  ![image](https://user-images.githubusercontent.com/24469318/210294144-f8db0bbb-d8a9-479f-9139-961d7f7814e2.png)

  - check status using Bash
  
 ![image](https://user-images.githubusercontent.com/24469318/210294247-e8299b35-e8ff-481b-bde3-b9f88e202cb8.png)
  
![image](https://user-images.githubusercontent.com/24469318/210294382-7eb7f527-5cd7-448c-911b-d70018ee3e8e.png)

![image](https://user-images.githubusercontent.com/24469318/210294434-8e058203-5605-4071-95ef-154e83a2bfa6.png)

  ![image](https://user-images.githubusercontent.com/24469318/210294526-dc59c272-99c7-4985-9490-97718d6e5439.png)

  
  Don't forget .\ at the beginning.
  
 ![image](https://user-images.githubusercontent.com/24469318/210294598-053376d4-f5d6-405f-87f9-0b48ccf70821.png)

  -Change IE enhanced sec config admin and user to off.
  
  ![image](https://user-images.githubusercontent.com/24469318/210294804-4f7d31a0-fc8f-4079-ba98-ee95836e6113.png)

  
  ![image](https://user-images.githubusercontent.com/24469318/210294890-b88257d1-ceb0-4593-a572-6b3cbd515f37.png)

  
  - This above demo is pending
  
  ![image](https://user-images.githubusercontent.com/24469318/210297011-52359424-7bf1-46df-b1c4-649a03b64307.png)
  
  - This command prepares the dotnet code and put result in folder name publish.
  
  ![image](https://user-images.githubusercontent.com/24469318/210297166-d345134f-387e-46d6-8bbf-9efef9d033e6.png)

  
  
  Setup for Weather VM
  
  ![image](https://user-images.githubusercontent.com/24469318/210318641-c74da346-ae60-49c5-8ef0-1d66679d7d4b.png)
  
 sudo apt update
  
 sudo apt install nodejs

 sudo git clone https://github.com/memilavi/weatherAPI.git
  
 sudo apt install npm
  
 cd node_modules - check what modules are installed.
  
 npm start
  
  
  
  ## Virtual Machine Tips and Tricks
  
 - If your VM needs more disks, in addition to the default one provided by Azure, then go to the Disks page for that, and add whatever disk you need. Don't forget that disks have costs, and check it in the calculator beforehand.

- Want to backup your VM so that it can be restored in a case of failure? Check the Backup page, where you can define the frequency of the backup and the retention period.

- You can define DNS name for the VM, so that it will be accessible not just using its IP. This can be done by clicking the DNS Name: Configure link in the Overview page.



  ![image](https://user-images.githubusercontent.com/24469318/210320113-330d0ac1-29c3-4173-bf45-a3fcd9d0a9b6.png)

  
 ![image](https://user-images.githubusercontent.com/24469318/210320161-db15e187-e181-4222-b85f-269c5ea993c2.png)

  
https://learn.microsoft.com/en-us/azure/architecture/icons/
  
  - Download SVG 
  
  # Our App Right Now
  
  ![image](https://user-images.githubusercontent.com/24469318/210320574-215135a1-5c9b-4a2d-aa23-985dd5f584e5.png)

  
  ![image](https://user-images.githubusercontent.com/24469318/210320708-07963098-2fcc-4ef1-abd5-3e531e4d8be5.png)

 
  
  - A quick reminder -

- If you're not planning on playing more with the VMs we just created (the Catalog VM and the Weather VM), then it might be a good idea to shut those machines down, so you will not pay for them when not in use.

- So in this case - simply shut them down.

- And now - let's go to App Services!

  
  
