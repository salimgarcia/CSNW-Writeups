# Domain User Writeup
Task Description: On your lab domain, create a standard account for yourself, and an admin account for performing administrative functions.

- Created two organizational units within my IT department organizational unit, one called Admins and the other called Users
- In the Admins OU I created a user called salim.admin, and in the Users OU I created one called salim.garcia
- In the Admins OU I created a group called IT_Adminstrators and added sadmin to the group
- Then I added the IT_Administrators group to the Domain Admins group so every user in the IT_Administrators group automatically has the same permissions as the default Administrator account
- In the users OU i created a group called IT_Users and added my user account salim.garcia to the group
- Then I added the group it the Domain Users group