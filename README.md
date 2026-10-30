# Sharing-Resources-mapping-drive-

What is NTFS (new technology file system)? 

NTFS is a windows file system for organizing files and folders. It allows for shared folders (via windows network sharing) to be available to users through file and folder permissions.  

Creating a shared folder allows users within the organization to save their data, which can be shared over the network with other users. This allows users to easily share files without ever having to manually send anything.  

Most organizations specify which users can access the shared folders by creating security groups. Only individuals in the group have access to the specific folder. Organizations will sometimes give users 1 specific personal folder for a user to use

Step 1: First, a shared folder can be created within the server's local drive. The helpdesk team will need to right click and then select New > Folder 

<img width="1118" height="706" alt="Screenshot 2026-10-24 124020" src="https://github.com/user-attachments/assets/c45151c6-0a64-4020-84d6-7441af629f46" />

Subfolders can then be made the same way within the overall folder. For example, I will be using a folder named "shares." I've created subfolders for 2 departments and a personal file for a specific user to access.  

<img width="908" height="221" alt="Screenshot 2026-10-24 124842" src="https://github.com/user-attachments/assets/3c103823-5adb-4406-9bc5-13838e8e503e" />

A folder can be shared to the network by right clicking on it > selecting properties > sharing> share> then share again.  

<img width="431" height="310" alt="Screenshot 2026-10-24 130523" src="https://github.com/user-attachments/assets/47b3c259-c2fa-417b-8163-a8d730225610" />

<img width="593" height="445" alt="Screenshot 2026-10-24 131011" src="https://github.com/user-attachments/assets/9f2d53a8-8a91-46af-bbfe-564bcea30d70" />

This green symbol signifies a shared file.  

<img width="257" height="100" alt="Screenshot 2026-10-24 131835" src="https://github.com/user-attachments/assets/8b785f37-45e5-4617-a784-4b14218e9c92" />

Step 2: Now that a shared folder was created, the folder can be associated with a security group for user access. Below, I created a security group within the AD users and computers tool. I first right clicked on the "Users" organizational unit. 

<img width="611" height="640" alt="Screenshot 2026-10-24 132343" src="https://github.com/user-attachments/assets/ebc8ac95-2162-40e9-b4f9-1fc96df6a8ff" />

<img width="427" height="372" alt="Screenshot 2026-10-26 225143" src="https://github.com/user-attachments/assets/bfe03984-b778-4f72-9393-67a42de321fc" />

Step 3: Now we need to allow the folder to be accessed by the HR security group. So, I'll go back to the HR file and allow access. I'll right click on HR then select properties.  

<img width="450" height="278" alt="Screenshot 2026-10-26 225413" src="https://github.com/user-attachments/assets/ffc29fde-30d2-43f7-82b3-02bf95ef2da0" />

Click on security then click Advanced. 

<img width="347" height="460" alt="Screenshot 2026-10-26 230936" src="https://github.com/user-attachments/assets/f7de6840-f53d-4934-acae-881ec0babb54" />

<img width="758" height="507" alt="Screenshot 2026-10-27 142903" src="https://github.com/user-attachments/assets/a66e8456-489c-470b-a8a7-60688d5645f2" />

<img width="910" height="590" alt="Screenshot 2026-10-27 143308" src="https://github.com/user-attachments/assets/527f7f1a-53f1-4512-9b50-17432ba7efac" />

For giving 1 user a personal folder this step would instead include the user's username rather than the security groups name. 

<img width="447" height="242" alt="Screenshot 2026-10-27 143413" src="https://github.com/user-attachments/assets/4fd17b57-e916-4381-853e-9df75db9e6c9" />

<img width="561" height="342" alt="Screenshot 2026-10-27 143455" src="https://github.com/user-attachments/assets/37be143f-be29-439f-8ccf-749878362178" />

Only allow members of this group to modify the files. With full control users would be able to change permissions and take ownership. 

<img width="907" height="585" alt="Screenshot 2026-10-27 143842" src="https://github.com/user-attachments/assets/b83602c1-e416-4b36-a602-574592481cce" />

Then select apply and ok 

Step 4: Now we want to find the users to add to the security group. For my example I will use aacre's account. 

Right click on the security group and select properties. 

<img width="472" height="286" alt="HR" src="https://github.com/user-attachments/assets/4846eb4b-c437-46f6-aaed-eab4681fee6b" />

Select members and then add 

<img width="392" height="447" alt="Screenshot 2026-10-27 144815" src="https://github.com/user-attachments/assets/e9067087-562f-4104-b6f7-e2f63597dd96" />

<img width="446" height="247" alt="Screenshot 2026-10-27 144539" src="https://github.com/user-attachments/assets/a7413b68-641c-4bf6-b0e1-a7bde211942c" />




