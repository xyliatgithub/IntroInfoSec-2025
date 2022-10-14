# Lab Assignment 3

In this lab assignment, you will need to complete the RSA Public-Key Encryption and Signature Lab module of the SEED Labs using Ubuntu 16.04 VM. The learning objective of this lab is for students to gain the first-hand experience on the RSA algorithm and the X.509 digital certificate. Coding experience is recommended, so you might want to work with someone with programming backgrounds. 


## Environment Setup

Go to [Lab Environment Setup page](https://seedsecuritylabs.org/lab_env.html) to install the pre-built VM image (Ubuntu 16.04 32 bits). You cannot work on it on your personal machine.  
- Install VirtualBox first, if you do not have it already
- VM setup instruction (read carefully): https://seedsecuritylabs.org/Labs_16.04/Documents/SEEDVM_VirtualBoxManual.pdf
- You only need one VM to do this lab, but you may still want to follow Appendix A to set up multiple VMs which will likely be used in future labs. For this lab, network configuration (explained in Appendix B) is also not needed, but will likely be needed for a future lab.
- User manual (contains the usernames and passowrds for the VM): https://seedsecuritylabs.org/Labs_16.04/Documents/SEEDVM_VirtualBoxManual.pdf

## RSA Public-Key Encryption and Signature Lab (50 points)

Please thoroughly go through the [lab description](https://seedsecuritylabs.org/Labs_16.04/PDF/Crypto_RSA.pdf) and complete all the tasks listed on it. We recommend you read the entire document before you start. You will need to write a detailed report with adequate screenshots and explanations, including your code and demonstration that your code can work. 
- Task 1 - 5 are coding tasks. You need to modify the example code given (section 2.2 in lab manual) to finish these tasks.
- For task 1 - 5, create a .c file for each of them. Then, compile the .c file you created using "gcc file_name.c -lcrypto" in the terminal. After compiling, a file is in the same directory called "a.out" if you do not specify the file name. Run the code using "./a.out". 
- The steps for completing these task is basically the same. Initialize BIGNUM variables you need, do the calculation using BN operation functions (e.g. a*b can be done using
	"BN_mul(res, a, b, ctx)").
- Pay attention to the lab manual, some tasks require to write your observations.

## Submission Details

- Due date of this assignment is announced on Canvas.
- Each group only needs to submit one report in PDF format.
- Please list group members in your report explicitly.
- Only typed reports are accepted.
- Make sure to include screenshots, codes, explainations, and observations in your report.

## Grading

- Completeness (30 pts): All the steps as instructed in the lab manual must be included in the report with adequate evidence.
- Presentation (20 pts): The report must be clear and correct in organization and writing with adequate explanation.
