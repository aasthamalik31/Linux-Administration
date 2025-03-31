<h1>
    🚀 Experiment 1 - 2 🚀
</h1>

<h3>
    1. Create the operator1 user and confirm that it exists in the system. Set the password for operator1. Create the additional operator2 and operator3 users. Set their passwords as well.
    <br><br>
    2. Run the usermod -c command to update the comments of the operator1 user account. Remove the operator3 user from the system.
</h3>

<hr>

<h1>
    Solution :
</h1>

<h5>Lab 1:</h5>
<p>1. Open the terminal and type:</p>
<i>sudo useradd operator1</i>
<br>
<img width="410" alt="image" src="https://github.com/user-attachments/assets/c2c11d98-6aca-49b4-b5f9-670544c46dd1" />


<p>2. To check whether or not the user is added:</p>
<i>sudo cat /etc/passwd</i>
<br>

<p>At the end of the file, you will be able to see:</p>
<img width="518" alt="image" src="https://github.com/user-attachments/assets/207c6d83-1f29-437d-bf20-ae1c37204da6" />


<p>3. To add the password:</p>
<i>sudo passwd operator1</i>
<br>

<p>4. Follow the same steps for operator2 and operator3 as well:</p>

![Screenshot 2025-03-25 103830](https://github.com/user-attachments/assets/434d496d-6ca7-44aa-8912-98676b8a7830)


<h5>Lab 2:</h5>
<p>1. To add comments to a particular user, type:</p>
<i>sudo usermod -c "Operator1's comment" operator1</i>
<br>

<img width="444" alt="image" src="https://github.com/user-attachments/assets/bc30100a-c757-4e6c-8c14-e45584e364cf" />


<p>2. To delete the user:</p>
<i>sudo userdel -r operator</i>
<br>

<img width="365" alt="image" src="https://github.com/user-attachments/assets/40fa7bfb-57e0-414a-b03d-6f378be47215" />


<h5>Creating Practice Files and Directories:</h5>
<p>Use the <i>touch</i> command to create sets of empty practice files:</p>
<i>touch song{1..6}.mp3 snap{1..6}.jpg film{1..6}.avi</i>

<img width="380" alt="image" src="https://github.com/user-attachments/assets/35bf8142-43ea-46db-9763-659ded85eb78" />


<p>Use a single command to create all three subdirectories:</p>
<i>mkdir monkey banana apple</i>

<img width="273" alt="image" src="https://github.com/user-attachments/assets/a783231e-fd59-4d38-9ca3-13dfece94d5c" />

