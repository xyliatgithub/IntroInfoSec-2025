# Lab Assignment 3

In this lab assignment, you will need to complete the RSA Public-Key Encryption and Signature Lab module of the SEED Lab Ubuntu 20.04 VM for Intel users and Ubuntu 22.04 for Apple Silicon users. The learning objective of this lab is for students to gain the first-hand experience on the RSA algorithm and the X.509 digital certificate. Coding experience is recommended, so you might want to work with someone with programming backgrounds.

## Environment Setup

### Intel/AMD Machines x86-64

1. Install VirtualBox first, https://www.virtualbox.org/ if you do not have it already. (Note: VirtualBox is available for most consumer computers, If you have trouble with this step, we encourage you to find a solution by yourself)
2. VM setup instructions (read very carefully): https://github.com/seed-labs/seed-labs/blob/master/manuals/vm/seedvm-manual.md
3. Go to [Lab Environment Setup page](https://seedsecuritylabs.org/labsetup.html) to install the pre-built VM image (for Ubuntu 20.04 VM 64 bits). You cannot work on it directly on your personal machine.
4. After building the VM, you can start the VM and log in with the username and password provided in the lab setup page.
5. For RSA Lab, download the lab specific zip file (Labsetup.zip) from the [lab page](https://seedsecuritylabs.org/Labs_20.04/Crypto/Crypto_RSA/). You can download it directly on the VM or download it on your host machine and transfer it to the VM using the shared folder feature of VMware Fusion.
6. Unzip the setup file and start your lab.

### Apple Silicon Machines ARM64

1. Install VMware Fusion first, https://blogs.vmware.com/teamfusion/2024/05/fusion-pro-now-available-free-for-personal-use.html if you do not have it already. (Note: VMware Fusion is available for Apple Silicon M chiip Macs, If you have trouble with this step, we encourage you to find a solution by yourself)
2. VM setup instructions (read very carefully): https://github.com/seed-labs/seed-labs/blob/master/lab-setup/apple-arm/seedvm-fusion.md
3. Go to [Lab Environment Setup page](https://seedsecuritylabs.org/labsetup.html) to install the pre-built VM image (for Ubuntu 22.04 VM 64 bits). You cannot work on it directly on your personal machine.
4. After building the VM, you can start the VM and log in with the username and password provided in the lab setup page.
5. For RSA Lab, download the lab specific zip file (Labsetup-arm.zip) from the [lab page](https://seedsecuritylabs.org/Labs_20.04/Crypto/Crypto_RSA/). You can download it directly on the VM or download it on your host machine and transfer it to the VM using the shared folder feature of VMware Fusion.
6. Unzip the setup file and start your lab.

## RSA Public-Key Encryption and Signature Lab (50 points)

Please thoroughly go through the [lab description](https://seedsecuritylabs.org/Labs_20.04/Files/Crypto_RSA/Crypto_RSA.pdf) and complete all the tasks listed on it. We recommend you read the entire document before you start. You will need to write a detailed report with adequate screenshots and explanations, including your code and demonstration that your code can work.

- Tasks 1 - 5 are coding tasks. You need to modify the example code given (section 2.2 in lab manual) to finish these tasks.
- For tasks 1-5, create a separate `.c` file for each task. Compile each `.c` file you've created using the command `gcc file_name.c -lcrypto` in the terminal (replace `file_name.c` with your actual file name). After compilation, if you haven't specified an output file name, an executable named `a.out` will be created in the same directory. Run the compiled program by entering `./a.out` in the terminal.
- The steps for completing these task is basically the same. Initialize BIGNUM variables you need, do the calculation using BN operation functions (e.g. a\*b can be done using
  "BN_mul(res, a, b, ctx)").
- Pay attention to the lab manual, some tasks require to write your observations.

## Submission Details

- Submit one PDF report per group by the due date announced on Canvas.
- Include a list of all group members and their specific contributions.
- Only typed reports will be accepted.
- Your report should contain screenshots, code snippets, explanations, and observations for each task.

## Grading

- Completeness (30 pts): All the steps as instructed in the lab manual must be included in the report with adequate evidence.
- Presentation (20 pts): The report must be clear and correct in organization and writing with adequate explanation.
