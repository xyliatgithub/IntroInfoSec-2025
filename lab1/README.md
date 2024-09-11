# Lab Assignment 1

In this lab, you will complete the XSS lab tasks from the SEED Labs. You will learn to code and attack a vulnerable social media application installed in a VM. Coding experience is recommended, so you might want to work with someone with relevant backgrounds.

## Environment Setup

### Intel/AMD Machines x86-64

1. Install VirtualBox first, https://www.virtualbox.org/ if you do not have it already. (Note: VirtualBox is available for most consumer computers, If you have trouble with this step, we encourage you to find a solution by yourself)
2. VM setup instructions (read very carefully): https://github.com/seed-labs/seed-labs/blob/master/manuals/vm/seedvm-manual.md
3. Go to [Lab Environment Setup page](https://seedsecuritylabs.org/labsetup.html) to install the pre-built VM image (for Ubuntu 20.04 VM 64 bits).
4. After building the VM, you can start the VM and log in with the username and password provided in the lab setup page.
5. Download the lab specific zip file (Labsetup.zip) from the [lab page](https://seedsecuritylabs.org/Labs_20.04/Web/Web_XSS_Elgg/). You can download it directly on the VM or download it on your host machine and transfer it to the VM using the shared folder feature of VirtualBox.
6. Unzip the setup file and start your lab.

### Apple Silicon Machines ARM64

1. Install VMware Fusion first, https://blogs.vmware.com/teamfusion/2024/05/fusion-pro-now-available-free-for-personal-use.html if you do not have it already. (Note: VMware Fusion is available for Apple Silicon M chiip Macs, If you have trouble with this step, we encourage you to find a solution by yourself)
2. VM setup instructions (read very carefully): https://github.com/seed-labs/seed-labs/blob/master/lab-setup/apple-arm/seedvm-fusion.md
3. Go to [Lab Environment Setup page](https://seedsecuritylabs.org/labsetup.html) to install the VM (Ubuntu 22.04).
4. After building the VM, you can start the VM and log in with the username and password provided in the lab setup page.
5. Download the lab specific zip file (Labsetup-arm.zip) from the [lab page](https://seedsecuritylabs.org/Labs_20.04/Web/Web_XSS_Elgg/). You can download it directly on the VM or download it on your host machine and transfer it to the VM using the shared folder feature of VMware Fusion.
6. Unzip the setup file and start your lab.

## Cross-Site Scripting (XSS) Attack Lab (50 points)

Please thoroughly read the [lab description](https://seedsecuritylabs.org/Labs_20.04/Files/Web_XSS_Elgg/Web_XSS_Elgg.pdf) and complete all the tasks listed in it. We recommend you first go through all the instructions before you start. You need to write a detailed report with adequate screenshots and explanations, including your code and demonstration that your attacks are successful. An example is given for what it would look like.

In addition, please answer the following questions:

1. In 3.2 task 1, why can we pop up a window using the first sample code provided in 3.2 Task 1? Please explain briefly how this happens. Is such an attack still possible in today's mainstream browsers? (To answer this question, you may need to search for any useful resources by yourself, and remember to provide the relevant evidence/references below.)

2. In 3.3 task 2, If your operation is correct, you will be able to see a "cookie" in the window that pops up. Please briefly explain why the code you add in this task allows you to see this "cookie".

## Submission Details

- Each group only needs to submit one report in PDF format.
- Please list group members in your report explicitly and each member's contribution.
- Only typed reports are accepted.
- Please ensure that you answer both the questions provided on this page (above) and those outlined in the lab instruction PDF.

## Grading

- Completeness (30 pts): All the steps as instructed in the lab manual must be included in the report with adequate evidence.
- Presentation (20 pts): The report must be clear and correct in organization and writing with adequate explanation.
