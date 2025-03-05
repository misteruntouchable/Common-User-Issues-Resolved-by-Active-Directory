# Common-User-Issues-Resolved-by-Active-Directory

### [Pictoral Walkthrough Demonstration]

<h2>Description</h2>
In this lab we are going to discuss common issues related to Users and Computers and ways to resolve these issuess using Active Directory.


<h2>Prerequisites</h2>
   For this lab we will not get into how to install virtual box or Active Directory. Oracle Box should be downloaded and installed, Windows Server 19 
   should have been downloaded and installed. Windows 10 should have been installed and Active Directory Domain Services be installed and configured 
   before this lab configuration.

 <h2>Languages and Utilities Used</h2>
  -<b>Microsoft Windows 10 Pro</b> 
 
  -<b>Oracle Virtual Box</b>
  -<b>Windows Server 19</b>

<h2>Environments Used </h2>

- <b>Windows 10(21H2)(/b)
- <b>Windows Server 2019</b>
-<b>Active Directory Users and Computers</b>

<h2>Program walk-through:</h2>
<p align="center">
  Finding Users and Computers in Active Directory: <br/>
 <img src="https://imgur.com/BMg0SUP.png" height="80%" width="80%" "/>
<p align="center"> In dealing with the different tasks of AD, the first thing we need resolve is how to find our Users, Computers or Printers etc. So we would 
                   go into User and Computers and right click on our domain, then click on "find", a box should open where you should see a drop down. The 
                   drop down will have different options of what you are trying to find whether its a person(users), computer, a printer etc. So after you 
                   have an option, let's say users, you can type in their first and last name. Then hit find now. This will automatically find the account 
                   that you are looking for. So if a user is lockout of their account and they need a password reset. You can right click on the User then go 
                   to properties. If you check the Users Account Tab, then check unlock users account and apply this should unlock the user's account.</br>
   
</br>

</br>                   
</br>

<p align="center">
  Unlocking the Users Account Active Directory (ie): <br/>
 <img src="https://imgur.com/TuL1xa4.png" height="80%" width="80%" "/>
<p align="center"> </br>   
   
   </br>
   </br>                   
   </br>

<p align="center">
   Another issue is when a User Forgets their Password and you have to perform a Reset: <br/>
 <img src="https://imgur.com/InUlefP.png" height="80%" width="80%" "/>
<p align="center"> In this you are going to right click on the User Name and then click reset the Password. Then type in the new password. Then check the 
   unlock the user's account  along with the User must change password at next login. Then click ok to apply</br>   
   
   </br>
   </br>                   
   </br>

<p align="center">
  User Reset Box (ie): <br/>
 <img src="https://imgur.com/TuL1xa4.png" height="80%" width="80%" "/>
<p align="center"> </br>
   
 
                   
   </br>
   </br>                   
   </br>

<p align="center">
   A third issue of Active Directory is the changing of a User's Profile: <br/>
 <img src="https://imgur.com/pMKtol1.png" height="80%" width="80%" "/>
<p align="center"> In this you are going to right click on the User Name then go to the properties. Then click the Profile type. Here if you want to change 
                   the description of the User, their is a prompt for that here. If you want to add a phone number you can also add it here.</br>   
   
   </br>
   </br>                   
   </br>

<p align="center">
   A fourth issue for Active Directory adding Users to a group: <br/>
 <img src="https://imgur.com/wqZmNXU.png" height="80%" width="80%" "/>
<p align="center"> In this you are going to right click on the User Name then go to the properties. Then click the Member Of tab. Here, you can click on 
                   then you can type in the name of the group, then check names of the Members of the group you want to add the User to , then ok and apply 
                   them to the group.</br>   
   
   
   </br> 
   </br>                   
   </br>

<p align="center">
    The last issue is we want to Creating a Service Account in Active Directory: <br/>
   <img src="https://imgur.com/ArPGwc4.png" height="80%" width="80%" "/>
  <p align="center"> A service account is a special type of user account that is used to runs services, automated processes and critical systems. The 
                     difference between service accounts and users accounts is that service account provides an identity to a service or a system, while   
                     a user account provides an identity for a person. So usually a computer or a server uses the service account while a person uses a user 
                     account. Service accounts are used for persistent programs that run continously like security cameras, display monitors etc. So in 
                     creating a Serivce Account you need to have a dedicated OU that is seperated from your user account. So create a seperate OU from the 
                      where the User Account you can name it "Security Accounts." After creating a seperate dedicated OU for the service account just right 
                      click, then go to new user. Name your service account with maybe a special character so its easy to tell if its a user account or a service 
                      account. Then next and type in a password, uncheck the user must change password at the next login, then click on password never expires.
                      Finally, when you have completed your service account right click on the name and add a description to the profile tab, the describe what the 
                      service is about.</br>   
   
   </br>
   </br>  
   
  
