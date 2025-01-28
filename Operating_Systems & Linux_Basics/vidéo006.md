## Title : Linux Commands and Groups (part 1)

Objectifs:
- User Accounts
- Groups & Ownership & File Permissions
- Linux Commands for Managing Users and their permissions

  <hr>
  
### Linux Accounts :

There are 3 categroies of user that you may have in Linux System : 

  **1. Superuser Account :**(root user)
  
   - unrestricted permissions
   - For admin tasks that need to login as Root user or execute commands as root (sudo command).

   **2. User Account :**(standard user)
   
    A regular user we create to login, e.g => /home/tom

   **3. Service Account :**

      Relevant for Linux Server Distros (like a database server or a web application server) and each service will get its own user.*

 Don't run services with root user. 

 Always **1 Root User per computer**.

 We can have **multiple** regular users and service users.

 min 9:46 Groups and permissions

How to manage Permissions in Linux ?

--> By 2 levels of permissions :

The 1st one by giving permissions to User Directely.

The 2nd one by Group Level : 

Group users into Linux Groups and give permissions to the group.

Exp, we have a devops team, a developer team, an admin team, so user will be added to each group and we will affect diffrent permissions for each group 

### User Management in practice (min 12:05)

sudo adduser tom

to check that the user is added, tape :

cat /etc/passwd



 
      
