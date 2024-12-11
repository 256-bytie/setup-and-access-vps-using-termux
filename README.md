# **Setup-and-access-vps-using-termux**
To set up and access this VPS using Termux, follow these steps:

**1. Install Required Tools in Termux**

Open Termux and ensure you have the necessary tools installed:

```bash
pkg update && pkg upgrade -y
pkg install openssh -y
```
**2. Generate the VPS Password**

• Open the email sent from your cloud company; to generate your VPS password or Copy give password.
• Save the password securely as you'll need it to connect via SSH.

**3. Connect to the VPS Using SSH**

Replace the placeholders with the "IPv4 address" and "username" (as provided in your email):

```bash

ssh ubuntu@51.75.161.254
```
  • Username: [yourusername]
  • IP Address: [youripadress] (as per the email)

**4. Enter the Password**

When prompted, enter the password you generated or given.

**5. Verify Connection**

If successful, you should see the terminal prompt of your VPS.

______________________________________________________________________________________________________________

**Tips**

• Ensure your Termux app has network permissions.
• Use a strong internet connection to avoid SSH timeouts.

Let me know if you encounter any errors during this process!
