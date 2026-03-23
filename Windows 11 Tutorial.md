# Windows 11 Installation Tutorial 
Welcome to the Windows 11 Installation Tutorial! This tutorial assumes you have read through the VirtualBox Tutorial. If not, click the link to read it, then come back.

https://github.com/jordanlim324/Virtual-Machine-Project/blob/main/VirtualBox%20Tutorial.md

# Installation Guide
1. Go to "https://www.microsoft.com/en-us/software-download/windows11" on your preferred browser of choice. Scroll until you see the selection to download a Windows 11 Disk Image (ISO) for x64 devices. Click confirm after selecting your edition.
<img width="1052" height="264" alt="Screenshot 2026-03-23 120752" src="https://github.com/user-attachments/assets/6ae83da8-ec2c-415e-8c28-c53d9ce988d3" />
<img width="1258" height="711" alt="image" src="https://github.com/user-attachments/assets/b565ac3b-66f0-4053-b2cc-6412b1b81882" />

2. Download your ISO file and note down where you have it saved.

3. In VirtualBox, press the "Add" button. Here you can add a name to your VM, save your VM to specified directory, and locate where you have the ISO saved. (In this case, I have it saved to an external drive.)
<img width="642" height="121" alt="image" src="https://github.com/user-attachments/assets/5405d6d3-f17e-45ee-8db6-7a14225830ca" />
<img width="968" height="584" alt="image" src="https://github.com/user-attachments/assets/c3f944a4-8049-4e71-9aeb-a4bcebe1df90" />

4. Move to "Unattended Install". Here you are able to add a password and set the Hostname of the system. (Note down your password somewhere and make sure your hostname has no spaces.)
<img width="968" height="584" alt="image" src="https://github.com/user-attachments/assets/33e79c77-f5b5-4cd7-946d-771ca4058f47" />

5. (Optional) Configure your Hardware and Hard Disk to your specification, otherwise these can remain default. Press Finish once configured.
<img width="968" height="584" alt="image" src="https://github.com/user-attachments/assets/333ad9c2-dc2a-4ead-8d2e-fbcac8a5cbb5" />
<img width="968" height="584" alt="image" src="https://github.com/user-attachments/assets/b1747a93-3c74-40e3-ab5a-64df246ee78f" />

6. Congratulations, you've installed Windows 11 on VirtualBox!
6a. If Windows asks for a product key, you may bypass it by clicking on "I do not have a product key."

7. Create a base snapshot for your OS by going to your OS, click on the three lines next to your VM, and going to Snapshots. Take a snapshot of your installation once you get into the desktop environment so that you can rollback if needed.

# Run Guide
1. Double click on your windows 11 isntallation in VirtualBox.
2. The VM will power on. It may take a while as it is going through the initial boot sequence.
3. Once the VM finishes the boot sequence, it will prompt you with a username and password.
By default, the credentials will be the login information created during step 4. <br>
4. You have now logged into Windows!
