# Creating & Managing Users in Active Directory

This guide explains how to create a new user and change their password in Active Directory using both the GUI (Active Directory Users and Computers) and PowerShell.

---

## Prerequisites

Before you begin, ensure you have the following:
1. Administrative access to the Active Directory environment.
2. Access to the domain controller or a machine with the **Active Directory Users and Computers (ADUC)** tool installed.


---

### Using Active Directory Users and Computers (GUI)

### Step 1: Open the Active Directory Users and Computers Tool
1. Press `Windows`, type and click **Active Directory Users and Computers**
2. Navigate to the appropriate Organizational Unit (OU) where the new user will reside.

---

### Step 2: Create a New User
1. Right-click on the OU and select **New > User**.
2. Fill out the user details:
   - **First name**: Enter the user's first name.
   - **Last name**: Enter the user's last name.
   - **User logon name**: Enter the logon name (e.g., `jdoe`).
3. Click **Next**.

![creating-user-ad](https://github.com/user-attachments/assets/59d3d9c2-887c-494c-9d1d-8bc6fe1c8137)

---

### Step 3: Set the User Password
1. Enter a password for the new user.
2. Choose password options:
   - **User must change password at next logon** (recommended).
   - **User cannot change password** (if needed).
   - **Password never expires** (not recommended unless necessary).
   - **Unlock the user's account** (if account has locked)
3. Click **Next** and then **Finish**.

![input-password-ad](https://github.com/user-attachments/assets/b75c97e2-89c1-42d0-9688-c5e1ef670732)


---

### Step 4: Change an Existing User's Password
1. Right-click on the user and select **Reset Password**.
2. Enter the new password and confirm it.
3. Click **OK**.

![right-click-password](https://github.com/user-attachments/assets/ec106c4c-a201-4af1-871a-b43d68e397da)

---

### Conclusion
Managing users in Active Directory is a fundamental task for system administrators. I hope I was able to share useful information.
