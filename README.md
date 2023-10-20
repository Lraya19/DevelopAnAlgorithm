<h1>Python - Develop an Algorithm</h1>


<h2>Description</h2>
Project consists of working as a security analyst and being responsible for developing an algorithm that connects users to their assigned devices. We’ll write code that indicates if a user is approved on the system and has brought their assigned device to the security team.
<br />


<h2>Languages and Utilities Used</h2>
 
- <b>Python</b>

<h2>Environments Used </h2>

- <b>Windows 11</b> (22H2)

<h2>Program walk-through:</h2>

<p align="center"> 
 <br/> We’ll work with a list of approved usernames along with a list of the approved devices assigned to these users. The elements of the two lists are synchronized. In other words, the user at index 0 in approved_users uses the device at index 0 in approved_devices. Later, this will allow us to verify if the username and device ID entered by a user correspond to each other.

<p align="center">
  Task 1:
  
  There’s a new employee joining the organization, and they need to be provided with a username and device ID.
  In the following code cell, we are given a username and device ID of this new user, stored in the variables new_user and new_device, respectively. We'll use the .append() method to add these variables to the approved_users and approved_devices respectively. Afterwards, we'll display the approved_users and approved_devices variables to confirm the added information.
<p align="center">
<img src="https://i.imgur.com/CsonNDw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Db2Sv58.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <p align="center">
    Task 2:
  
  An employee has left the team and should no longer have access to the system. In the following code cell, we are given the username and device ID of the user to be removed, stored in the variables removed_user and removed_device respectively. We'll use the .remove() method to remove each of these elements from the corresponding list. Afterwards, we'll display both the approved_users and the approved_devices variables to view the removed users.
  <p align="center">
<img src="https://i.imgur.com/0IbCQ1g.png" height="80%" width="80%">

<p align="center">
    Task 3:
  
 As part of verifying a user’s identity in the system, we’ll need to check if the user is one of the approved users. We'll write a conditional statement that verifies if a given username is an element of the list of approved usernames. If it is, we'll display “The user ______ is approved to access the system.” Otherwise, we'll display “The user ______ is not approved to access the system.”
  <p align="center">
<img src="https://i.imgur.com/Kif6V2H.png" height="80%" width="80%">

<p align="center">
    Task 4:
  
 The next part of the algorithm uses the .index() method to find the index of username in the approved_users and store that index in a variable named ind.
 When used on a list, the .index() method will return the position of the given value in the list. We'll add a statement to display ind in the following code cell to explore the value it contains.
  <p align="center">
<img src="https://i.imgur.com/XiMTeNK.png" height="80%" width="80%">

<p align="center">
    Task 5:
  
 This task will allow us to build our understanding of list operations for the algorithm that we’ll eventually build. It will demonstrate how we can find an index in one list and then use this index to display connected information in another list.
 First, we'll use the .index() method again to find the index of username in the approved_users and store that in a variable named ind. Then, we'll connect ind to the approved_devices and display the device ID located at the index ind. 
  <p align="center">
<img src="https://i.imgur.com/wH1YzjB.png" height="80%" width="80%">

<p align="center">
    Task 6:  
  
 Our next step in creating the algorithm is to determine if a username and device ID correspond. To do this, we'll write a conditional that checks if the username is an element of the approved_devices and if the device_id stored at the same index as username matches the device_id entered. We’ll use the logical operator 'and' to connect the two conditions. When both conditions evaluate to True, we'll display a message that the username is approved and another message that the user has their assigned device.
  <p align="center">
<img src="https://i.imgur.com/eyTwKWt.png" height="80%" width="80%">

<p align="center">
    Task 7:  
  
It would also be helpful for users to receive messages when their username is not approved or their device ID is incorrect. We'll add to the code by writing an elif statement. This elif statement should run when the username is part of the approved_users but the device_id doesn’t match the corresponding device ID in the approved_devices. The statement should also display two messages conveying that information.
  <p align="center">
<img src="https://i.imgur.com/JGEPkFz.png" height="80%" width="80%">
<img src="https://i.imgur.com/bx7UFkT.png" height="80%" width="80%">

<p align="center">
    Task 8:  
  
In this task, we’ll complete our algorithm by developing a function that uses some of the code we’ve written in earlier tasks. This will automate the login process.

There are multiple ways to use conditionals to automate the login process. In the following code, a nested conditional is used to achieve the goals of the algorithm. There is a conditional statement inside of another conditional statement. The outer conditional handles the case when the username is approved and the case when username is not approved. The inner conditional, which is placed inside the first if statement, handles the case when the username is approved and the device_id is correct, as well as the case when the username is approved and the device_id is incorrect.
To complete this task, we must define a function named login that takes in two parameters, username and device_id.
  <p align="center">
<img src="https://i.imgur.com/QOzIWtI.png" height="80%" width="80%">
<img src="https://i.imgur.com/86NyBh3.png" height="80%" width="80%">

<p align="center">
    Conclusion:  

Developing algorithms in Python offers numerous advantages for cybersecurity analysts. Firstly, Python’s simplicity and readability make it an ideal choice for quickly prototyping and implementing security solutions. Its extensive library ecosystem streamlines the development of machine learning-based intrusion detection systems. Python’s cross-platform compatibility ensures that these algorithms can be easily deployed on various operating systems.


     
<br /> 
<br />
    
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
