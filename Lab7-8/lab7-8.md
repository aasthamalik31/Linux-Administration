<h1>
  🚀 LAB 7-8 🚀
</h1>

<h2>
  1. Create the /home/consultants directory.
    <br><br>
  2. Add write permission to the consultants group using the symbolic method for setting permissions.
    <br><br>
  3. Forbid others from accessing files in the /home/consultants directory using the octal method.
    <br><br>
  4. Change the default umask for the operator1 user to prohibit all access for users not in their group. Confirm the umask is changed.
</h2>

<hr>

<h3>
  Solution :
</h3>

<h5>
  Lab 7:
</h5>

<b>Step 1:</b> Open the terminal and type:
   <i>
     sudo mkdir /home/consultants
   </i>

  ![image](https://github.com/user-attachments/assets/5fdcd3d8-3585-49e8-8dbf-46e6026770fb)



<b>Step 2:</b> To add write permission for the consultants group:
   <i>
     sudo chmod g+w /home/consultants
   </i>

   ![image](https://github.com/user-attachments/assets/cdd986aa-d753-48e5-9ae2-9ec4723eef2e)


<b>Step 3:</b> To forbid others from accessing the directory (octal method):
   <i>
     sudo chmod 770 /home/consultants
   </i>

   ![image](https://github.com/user-attachments/assets/2bf3fa56-aa85-4136-9d41-fb725d889da1)



<h5>
  Lab 8:
</h5>

<b>Step 1:</b> To change the default umask for operator1:
   <i>
     sudo usermod -s "/bin/bash" operator1
   </i>

   ![image](https://github.com/user-attachments/assets/b4628a2f-2f32-483c-bb91-7668efb5ed10)


<b>Step 2:</b> Edit the profile file to update the umask:
   <i>
     sudo nano /home/operator1/.profile
   </i>
   
![image](https://github.com/user-attachments/assets/bc920df4-6560-4bdf-a3e0-03d80c055cef)


<b>Step 3:</b> Add the following line to set umask:
   <i>
     umask 007
   </i>

   ![image](https://github.com/user-attachments/assets/a5c84e06-abd3-4f67-8507-0d7a6ca059c2)


<b>Step 4:</b> Save and exit, then verify using:
   <i>
     umask
   </i>

   ![image](https://github.com/user-attachments/assets/cbbf3ec0-25b0-48f3-90bd-53f1132836c2)

