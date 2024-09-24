# Lab Assignment 5 - Data Privacy

This lab assignment studies data privacy issues using a tool called ARX on a SEED VM. In this lab, you will learn data anonymization by applying the k-anonymity model.

## Lab Manual and Datasets

The lab manual and several datasets are available on Canvas. You will find a set of questions and tasks in the lab manual.

### Acknowledgement

This lab is adopted with some minor revisions from the material by Dr. Mengjun Xie at the University of Tennessee at Chattanooga and Dr. Na Li at Prairie View A&M University.

## Environment Setup

### Intel/AMD Machines x86-64

1. Install VirtualBox first, https://www.virtualbox.org/ if you do not have it already. (Note: VirtualBox is available for most consumer computers, If you have trouble with this step, we encourage you to find a solution by yourself)
2. VM setup instructions (read very carefully): https://github.com/seed-labs/seed-labs/blob/master/manuals/vm/seedvm-manual.md
3. Go to [Lab Environment Setup page](https://seedsecuritylabs.org/labsetup.html) to install the pre-built VM image (for Ubuntu 20.04 VM 64 bits). You cannot work on it directly on your personal machine.

#### Install ARX on the SEED VM:

1. Open the VM.
2. In your VM, go to the ARX download website: https://arx.deidentifier.org/downloads/.
3. From Anonymization Tool -> Installer, download the `Linux/GTK 64bit` version of the ARX.
4. After download the ARX, in you VM file folder, open the terminal.
5. Use the command `chmod +x ARX-3.9.1-linux-x64-installer.run` to make your RUN file executable.
6. Use the command `./ARX-3.9.1-linux-x64-installer.run` to execute your RUN file for downloading the ARX tools on your SEED VM.
7. Downbload the zip file containing the datasets to be used and save them on the VM.

### Apple Machines

#### Install ARX locally:

1. In your VM, go to the ARX download website: https://arx.deidentifier.org/downloads/.
2. From Anonymization Tool -> Installer, download the `MacOS 64-Bit` version of the ARX.
3. After download the ARX, open the folder where the ARX zip file is downloaded.
4. Use the command `unzip ARX-3.9.1-osx-installer.app.zip` to unzip the file.
5. Use the command `cd ARX-3.9.1-osx-installer.app/Contents/MacOS` to get find the installer file `installbuilder.sh`.
6. Use the command `chmod +x installbuilder.sh` to make your SH file executable.
7. An alert will then pop up, stating:

```
Apple could not verify “ARX-3.9.1-osx-installer” is free of malware that may harm your Mac or compromise your privacy.
```

8. Open the `System Preferences` -> `Security & Privacy` -> `General` -> `Open Anyway` to allow the installation.

9. After the installation, you can find the ARX tool in the Applications folder.

## Submission Details

- Each group only needs to submit one report in PDF format.
- Please list group members in your report clearly.
- Only typed reports are accepted.
- Make sure to include screenshots, explanations, and all your answers to all the questions in your report.

## Grading

- Completeness (30 pts): All the steps as instructed in the lab manual must be included in the report with adequate evidence.
- Presentation (20 pts): The report must be clear and correct in organization and writing with adequate explanation.
