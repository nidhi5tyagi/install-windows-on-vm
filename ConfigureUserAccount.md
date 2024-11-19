## Step 1: Configure User Accounts (Alice and Bob)

### Alice (Administrator)
1. **Login as Alice** (Administrator) after Windows setup completes.
2. Open **Settings** > **Accounts** > **Family & Other Users**.
3. Click **Add Account**.
4. Create a **Microsoft account** or **Local Account** for Alice. Ensure Alice has **Administrator** privileges.

### Bob (Restricted User)
1. **Login as Alice** (Administrator).
2. Open **Settings** > **Accounts** > **Family & Other Users**.
3. Click **Add Account**.
4. Create a **Microsoft account** or **Local Account** for Bob.
5. Under **Account Type**, choose **Standard User** to give Bob restricted access.
6. Set Bob's folder location to **C:\Users\Bob**.

### Folder Permissions for Bob
1. Press **Win + E** to open **File Explorer**.
2. Navigate to **C:\Users\Bob**.
3. Right-click the **Bob folder** and select **Properties**.
4. Under the **Security** tab, click **Edit** to set permissions.
5. Give Bob **Read, Write, and Execute** permissions for his folder.

---

## Step 2: Install Antivirus and Firewall

### Antivirus Installation
1. **Windows Defender** (built-in):
   - Windows 11 comes with **Windows Defender** Antivirus. Make sure it's enabled by default.
   - Go to **Settings** > **Privacy & Security** > **Windows Security** > **Virus & Threat Protection**.
   - Ensure that **Real-Time Protection** and **Cloud-Delivered Protection** are enabled.
   
2. **Third-Party Antivirus (optional)**:
   - You can install third-party antivirus software like **Avast**, **Kaspersky**, or **Bitdefender** if you prefer.
   - Download the antivirus software from the official website and follow the installation instructions.

### Firewall Configuration
1. **Windows Firewall** (enabled by default):
   - Go to **Control Panel** > **System and Security** > **Windows Defender Firewall**.
   - Ensure the firewall is enabled for both **Private** and **Public** networks.

2. **Additional Firewall (optional)**:
   - You can install third-party firewall software like **ZoneAlarm** or **Comodo** if needed.
   - After installation, configure it to block incoming and outgoing traffic based on your preferences.

---

## Step 3: Final Configuration and Optimization

- **Check for Windows Updates**: 
  - Go to **Settings** > **Windows Update** and make sure your system is fully updated.

- **Install Drivers and Utilities**:
  - For Apple Silicon Macs, ensure that the UTM is configured to use ARM-based drivers for better performance.
  - You may need to install QEMU drivers or other utilities for smoother performance and compatibility.

---

## Conclusion

Windows 11 is now installed on your UTM VM with two users:
- **Alice**: Administrator with full access.
- **Bob**: A standard user with restricted access to only his folder.

The system is also protected with **Windows Defender Antivirus** and **Windows Firewall**, providing basic security for the virtual machine.
