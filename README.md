# Windows 10 Local Users & Permissions Lab

## 🛡️ Στόχος

Δημιουργία ενός μικρού εργαστηριακού περιβάλλοντος σε **Windows 10**, όπου έγινε έλεγχος και σύγκριση δικαιωμάτων μεταξύ **Administrator** και **Standard User** λογαριασμών.

Πραγματοποιήθηκαν δοκιμές σε:

* Local Users & Groups
* Windows Services
* Windows Update
* Event Viewer
* NTFS Folder Permissions

Σκοπός: πρακτική εξάσκηση σε **Windows Administration, Access Control, Troubleshooting και IT Support skills**.

---

## 🖥️ Περιβάλλον

* OS: Windows 10 Pro
* User Accounts:
  * Administrator
  * Standard User
* Tools:
  * Local Users & Groups (lusrmgr.msc)
  * Services
  * Event Viewer
  * Windows Update
  * File Explorer (NTFS Permissions)

---

## 🔧 Lab Activities

### Local Users & Groups

Verified Administrator and Standard User accounts using **Local Users & Groups**.

**Screenshots**

**Administrator Role**

* [Open Computer Management](./screenshots/Computer-Management.png)
* [Open Local Users & Groups](./screenshots/Users.png)
* [View Administrator Account](./screenshots/Users-1.png)
* [Verify Administrator Group Membership](./screenshots/Users-Properties.png)

**Standard User Role**

* [Create Standard User](./screenshots/Create-Standard-User.png)
* [Complete User Creation](./screenshots/Complete-User-Creation.png)
* [Verify User in Computer Management](./screenshots/Verify%20User%20in%20Computer%20Management.png)
* [Verify User Group Membership](./screenshots/Verify-User-Group-Membership.png)

**Result**

* Administrator account confirmed through Administrators group membership.
* Standard User account confirmed through Users group membership.
---

### Windows Services

Compared Administrator and Standard User permissions when managing **Windows Services**.

**Screenshots**

**Administrator**

* [Open Services Console](./screenshots/Open-Services-Console.png)
* [View Service Properties](./screenshots/View-Service-Properties.png)
* [Administrator Service Access](./screenshots/Administrator-Service-Access.png)
* [Verify Service Control Permissions](./screenshots/Verify-Service-Control-Permissions.png)

**Result**

* Administrator accounts can start, stop and configure Windows services.
* Managing protected system services requires administrative privileges.
---

### Windows Update

Tested Windows Update permissions using a Standard User account.

**Screenshot**

* [Open Services Console](./screenshots/Services.msc-Standard.png)
* [View Service Properties](./screenshots/Properties-Standard.png)
* [Windows Update - Standard User](./screenshots/windows-update-pause-standard.png)

**Result**

* Standard users can pause Windows Updates for up to 7 days.
* Advanced Windows Update settings require Administrator privileges.

---

### Event Viewer

Reviewed Windows Event Logs using a Standard User account.

**Screenshots**

**Standard User**

* [Open Event Viewer](./screenshots/Open-Event-Viewer.png)
* [View Windows Event Logs](./screenshots/View-Windows-Event-Logs.png)
* [Verify Standard User Access](./screenshots/Verify-Standard-User-Access.png)

**Events Reviewed**

* Kernel-General
* WindowsUpdateClient

**Result**

* Standard Users can review Windows Event Logs for troubleshooting.
* Viewing logs does not require administrative privileges.
**Result**

Verified that Standard Users can inspect Windows Event Logs for troubleshooting purposes without administrative privileges.

---

### NTFS Folder Permissions

Created a shared folder and compared Administrator vs Standard User permissions.

**Screenshots**

* [Folder Creation](./screenshots/labfolder-create.png)
* [Folder Permissions](./screenshots/labfolder-permissions.png)

**Result**

* Administrator accounts have Full Control and can modify permissions.
* Standard Users have Read or Modify access only when explicitly granted.
* Demonstrated practical use of NTFS permissions and access control.

---

## 🧠 Τι Έμαθα

* Configure Administrator and Standard User accounts.
* Understand Windows privilege separation.
* Compare Windows Services permissions.
* Review Windows Event Viewer logs.
* Test Windows Update permission differences.
* Configure and verify NTFS folder permissions.
* Understand Windows access control and security concepts.

---

## 🛠️ Tools

| Tool | Purpose |
|------|---------|
| Windows 10 Pro | Lab environment |
| Local Users & Groups | User and group management |
| Windows Services | Service management |
| Event Viewer | System log analysis |
| Windows Update | Update management |
| NTFS Permissions | Folder access control |

---

## 💼 CV Entry

Configured Administrator and Standard User accounts, verified Local Users & Groups membership, compared Windows Services permissions, tested Windows Update restrictions, reviewed Event Viewer logs and configured NTFS permissions to demonstrate Windows administration, access control and troubleshooting skills.

---

## 👤 About me

📍 Τεχνικός Υπολογιστικών Συστημάτων, ειδίκευση σε **Windows Administration, Networking, Linux και IT Support**

📫 LinkedIn / Email:

[LinkedIn Profile](https://www.linkedin.com/in/%CE%B5%CE%BC%CE%BC%CE%B1%CE%BD%CE%BF%CF%85%CE%B7%CE%BB-%CE%BA%CE%B1%CE%BD%CE%B1%CE%BA%CE%B7%CF%82-695809356/)

[kanakismanolis04@gmail.com](mailto:kanakismanolis04@gmail.com)
