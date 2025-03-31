<h1>
  🚀 LAB 3 - 4 🚀
</h1>

<h3>
  1. View the gedit man page.<br><br>
  2. Use the man -k ext4 command to find the command to tune ext4 file-system parameters.<br><br>
  3. Understand and demonstrate the use of brace expansion.
</h3>

<hr>

<h1>
  Solution : 
</h1>

<h5>
  Lab 3: 
</h5>

  1. Open the terminal and type:
     <i>
       man gedit
     </i>
     
     <img width="190" alt="image" src="https://github.com/user-attachments/assets/85894c7a-97a3-4018-a375-2490ab8c03da" />



  2. If the manual page is not available, try installing `gedit` first:
     <i>
       sudo apt update && sudo apt install gedit
     </i>
     
     <img width="492" alt="image" src="https://github.com/user-attachments/assets/13430e88-58b0-41c0-af0d-0fa308040b5f" />

<h5>
  Lab 4:
</h5>

  1. To search for commands related to ext4, type: <br>
     <i>man -k ext4</i>
     
     <img width="800" alt="image" src="https://github.com/user-attachments/assets/e0afee7f-3a60-43b9-84ba-3d21b03737be" />


  2. To find the command to tune ext4 file systems, look for `tune2fs` in the output and check its manual page:
     <i>man tune2fs</i>
     
     <img width="205" alt="image" src="https://github.com/user-attachments/assets/2a319d57-e215-4f88-90ea-769ffcc6bcce" />



  3. Understanding Brace Expansion: <br>
     <i>echo file{1,2,3}.txt</i><br>
     Output:
     <pre>file1.txt file2.txt file3.txt</pre>

     <img width="244" alt="image" src="https://github.com/user-attachments/assets/33932dc0-d6d3-4ff9-8ee7-36c79e984f65" />



  4. Using a sequence expression:
     <i>echo file{1..5}.txt</i>

     ![image](https://github.com/user-attachments/assets/d0d08652-49ad-41d7-8919-6929427bdd66)


     
