# Basic Windows Defender Configuration

## Table of Contents
1. Introduction
2. Accessing Windows Defender
3. Turning on Real-time Protection
4. Configuring Virus & Threat Protection
5. Exclusions Management
6. Firewall & Network Protection
7. Configuring App & Browser Control
8. Updating Security Definitions
9. Notifications Configuration
10. Conclusion

---

## 1. Introduction
Microsoft Defender Firewall is one of the security features that protect your computer and network against unwanted traffic. It works as a stateful firewall by keeping tabs on active connections to determine whether to allow or block traffic following specific rules. 

Firewalls can be categorized into two types: stateful and stateless. Windows Defender Firewall is a stateful firewall.

![Main](https://github.com/user-attachments/assets/f6ef0033-42c9-4723-991c-bee8a8d92133)

## 2. Accessing Windows Defender
1. Press `Win + I` to open **Settings**.
2. Navigate to **Update & Security**.
3. On the left pane, select **Windows Security**.
4. Click on **Open Windows Security**.

## 3. Turning on Real-time Protection
1. From the Windows Security home screen, click on **Virus & Threat Protection**.
2. Under the **Virus & Threat Protection Settings**, select **Manage settings**.
3. Ensure that **Real-time Protection** is toggled on. This setting ensures active protection against malware in real-time.

## 4. Configuring Virus & Threat Protection
1. Navigate to **Virus & Threat Protection**.
2. Under the **Virus & Threat Protection Settings**, you can customize:
   - **Cloud-delivered protection**: Ensures that your device uses up-to-date intelligence for detecting threats.
   - **Automatic sample submission**: Sends suspicious files to Microsoft for analysis.

To enable these:
1. Go to **Manage Settings**.
2. Toggle on **Cloud-delivered protection** and **Automatic sample submission**.

## 5. Exclusions Management
Sometimes, certain files, folders, or applications may be incorrectly flagged. You can add exclusions as follows:
1. From **Virus & Threat Protection Settings**, scroll down to **Exclusions**.
2. Click on **Add or remove exclusions**.
3. Choose the type of exclusion (file, folder, file type, or process).
4. Browse and add the desired exclusion.

## 6. Firewall & Network Protection
To ensure network protection:
1. From the Windows Security dashboard, select **Firewall & network protection**.
2. Ensure that the **Domain network**, **Private network**, and **Public network** firewalls are toggled **On**.
3. For more detailed firewall configuration, click on the network type and adjust advanced settings, such as blocking incoming connections or configuring app access.

## 7. Configuring App & Browser Control
Windows Defender provides protection when downloading files and browsing the web:
1. Go to **App & Browser Control** from the Windows Security dashboard.
2. Under **Check apps and files**, set the control to either **Warn** or **Block**.
3. Enable **Exploit Protection** by clicking on **Exploit Protection Settings** at the bottom and configuring the system and program settings as per your needs.

## 8. Updating Security Definitions
To ensure the latest protection:
1. From the Windows Security dashboard, go to **Virus & Threat Protection**.
2. Scroll down and click **Check for updates** under **Virus & Threat Protection Updates**.
3. Ensure Windows Defender is up to date to protect against the latest threats.

![Inboud Rules](https://github.com/user-attachments/assets/5072ede4-ad68-4915-bc71-77fcc3078506)
![Outbound Rules](https://github.com/user-attachments/assets/c52502be-8572-4be1-830b-a68717293267)


## 9. Notifications Configuration
To manage Defender notifications:
1. In Windows Security, go to **Settings** (gear icon on the bottom left).
2. Select **Manage notifications**.
3. Here, you can turn on or off notifications related to various Windows Defender activities, such as alerts for malware found, periodic scans, etc.

![Monitoring](https://github.com/user-attachments/assets/1d51c916-c57d-4673-9869-cb3fd9a27e2d)

## 10. Conclusion
Windows Defender offers a robust layer of security for your Windows machine. By following the steps outlined above, you can ensure that your system is adequately protected from potential threats while having the flexibility to configure specific settings based on your requirements.
