<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Active Directory: Real-World Scenario Simulation – Phase 4</h1>

<p>Welcome to the final phase of our Active Directory lab series! After setting up the infrastructure, deploying AD, and creating users, it’s time to see how everything works together. In this phase, we’ll put our AD environment to the test by simulating everyday tasks that IT admins handle. We’ll create user accounts, reset passwords, update group memberships, deactivate accounts, and manage OUs. This phase brings together all the pieces from the previous steps and shows how to manage a real-world AD setup.</p>

<h2>Key Objectives</h2>

<h4>Scenario Simulation</h4>
- Practice real-world AD management tasks like creating users, updating groups, and handling account deactivation.

<h4>Troubleshooting Scenarios</h4>
- Work through common AD issues like password resets and access problems.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines)  
- Remote Desktop  
- Active Directory Domain Services  

<h2>Operating Systems Used</h2>

- Windows Server 2022  
- Windows 10 (21H2)  

<h1>Scenarios</h1>

<h3>&#9312; User Account Creation</h3>

<h4>Background:</h4>
<p>A new developer, John Smith, has joined the IT department. We need to create his user account in Active Directory.</p>

<p><strong>Create a new user account named "John Smith" with the username "john_smith" and a temporary password.</strong></p>

![ss1](https://github.com/user-attachments/assets/833c4eed-eac6-4f1c-9102-fa44b575d139)

<p><strong>NOTE: Set the account to require a password change at the next login.</strong></p>

<p><strong>Assign John to the "Developers" security group in AD.</strong></p>

![ss2](https://github.com/user-attachments/assets/3089581d-2099-4fe0-be34-be1ede5232b8)

<p><strong>Place John's account in the correct Organizational Unit (OU) for IT staff.</strong></p>

![ss3](https://github.com/user-attachments/assets/dbc72b13-0725-46e5-8f08-aba9057e929b)

<p><strong>After creating John's credentials, securely communicate the login information and temporary password to him, and document the date and time of account creation for auditing purposes.</strong></p>

<h4>Considerations:</h4>

- Make sure the password meets policy requirements.  
- Confirm that John has the necessary permissions for his role.  

<h3>&#9313; Password Reset</h3>

<h4>Background:</h4>
<p>Emily Carter, a marketing associate, contacted the IT help desk because she forgot her password and can’t log in to her computer or email. The help desk needs to reset her password in Active Directory so she can get back to work.</p>

<p><strong>Locate Emily's user account and initiate a password reset.</strong></p>

![ss4](https://github.com/user-attachments/assets/35a148b7-9c9d-4850-bb2e-76820e77c29c)

<p><strong>Set a temporary password that complies with the company policy.</strong></p>

![ss5](https://github.com/user-attachments/assets/71b098f0-0a40-415d-b7d8-5d8ff97c6338)

<p><strong>NOTE: Make sure to click the highlighted boxes to ensure the user’s account is unlocked and enable them to set their own password. </strong></p>

<p><strong>Communicate the temporary password to Emily through a secure channel, instruct her to change it immediately upon login, and provide guidance on using the company’s self-service password reset tool if available; also, document the date and time of account creation for auditing purposes.</strong></p>

<h4>Considerations:</h4>

- Ensure the new password is strong and policy-compliant.  
- Advise Emily to update her saved passwords on other devices.  

<h3>&#9314; Group Membership Update </h3>

<h4>Background:</h4>

<p>Sophia Chen, a systems analyst, was recently promoted to a manager in the IT department. She now needs access to certain network resources and project folders. The IT help desk needs to update her group memberships in Active Directory to reflect her new role.</p>

<p><strong>Locate Sophia's user account and review her current group memberships.</strong></p>

![ss6](https://github.com/user-attachments/assets/119c98f9-0095-4817-bddc-bb4c7c19ba5b)

<p><strong>Remove Sophia from the "Systems Analysts" group and add her to the "IT Managers" group.</strong></p>

![ss7](https://github.com/user-attachments/assets/c49d4087-248c-498f-8223-581a3c3b196a)

<p><strong>Confirm that Sophia now has the necessary access rights to project folders and relevant network resources.</strong></p>

![ss8](https://github.com/user-attachments/assets/01726ebb-95b6-4100-b30f-d0a2c8c8bcbb)

- Communicate the group membership update to Sophia, along with any additional instructions or changes in access.
- Document the whole process


<h4>Considerations:</h4>

- Ensure that Sophia's new group memberships align with her managerial responsibilities.
- Communicate the changes to other relevant parties, such as the IT security team, to maintain awareness.
- Verify that Sophia's access permissions are correctly configured after the group membership update.

<h3>&#9315; Account Deactivation </h3>

<h4>Background:</h4>

<p>Michael Kim, a network administrator, has recently left the company. The IT help desk needs to deactivate his user account in Active Directory to keep company resources secure and prevent unauthorized access.</p>

<p><strong>Locate Michael's user account and initiate the account deactivation process.</strong></p>

![ss9](https://github.com/user-attachments/assets/13a5aaed-2bbe-4747-88d0-2696c7fb65c9)

<p><strong>Disable Michael's account to prevent further logins while retaining the account details for reference.</strong></p>

![ss10](https://github.com/user-attachments/assets/c6282cea-1d89-4710-9e95-46d8259bbd21)

<p><strong>You may receive a confirmation dialog; click "Yes" to confirm the disabling of the user account.</strong></p>

![ss11](https://github.com/user-attachments/assets/5436d20a-d5ca-4af5-87d4-067b363e6c5e)

<p><strong>Remove Michael from all security groups to revoke his access to network resources.</strong></p>

![ss12](https://github.com/user-attachments/assets/23850498-ff33-48f3-a905-7fc045d5036e)

<p><strong> Confirm with other relevant departments (e.g., HR) that Michael's departure aligns with company policies and document the whole process.</strong></p>

<h4>Considerations:</h4>

- Ensure a smooth transition of Michael's responsibilities to other team members.

-  Communicate the account deactivation to other departments, such as HR and security, for coordinated efforts.

-  Retain Michael's user account details for historical records and potential future reference.
   
-  Conduct a review of Michael's access rights to identify and update any shared resources associated with his account.

<h3>&#9316; Organizational Unit (OU) Management </h3>

<h4>Background:</h4>

<p>The Sales department was reorganized, and a new International Sales team was created. The IT help desk needs to update Active Directory by creating a new Organizational Unit (OU) for the team and moving the right user accounts into it.</p>

<p><strong>Create a new Organizational Unit named "International Sales" within the Sales department's organizational structure.</strong></p>

![ss13](https://github.com/user-attachments/assets/cafed72d-b512-4a21-97e2-008a3f34aed0)

<p><strong>Move the user accounts of team members, such as Daniel Brooks and Ava Martinez, to the newly created OU.</strong></p>

![ss14](https://github.com/user-attachments/assets/aa7a24a1-9296-4193-b9fd-07dffe4757e6)

<p><strong> Verify that the users now appear under the "International Sales" OU in Active Directory.
</strong></p>

![ss15](https://github.com/user-attachments/assets/2b25af87-abdc-4087-b581-88a65eec3596)

<p><strong>Communicate the organizational change to relevant stakeholders, such as department heads and team leaders.
</strong></p>

<h4>Considerations:</h4>

- Ensure that the new OU structure aligns with the company's organizational hierarchy.
- Confirm that the appropriate Group Policy settings apply to the users within the new OU.
- Communicate any changes in access permissions or policies resulting from the OU reorganization to the IT security team.


<h2>Final Thoughts</h2>

<p>
This final phase concludes the 4-part Active Directory project series. In this stage, we applied key AD tasks such as creating users, managing group memberships, resetting passwords, deactivating accounts, and organizing users into OUs. These hands-on scenarios reflect real-world responsibilities and reinforce practical skills essential for managing Active Directory environments.
</p>
