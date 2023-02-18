# Week 0 — Billing and Architecture

## Required Homework

### Installing AWS CLI
I was unable to use GITPOD, so I have configured AWS CLI on my local machine

I followed the instruction on the AWS documentation page of [how to install AWS CLI for windows](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html)

I copied the following line of code and ran it in the cmd in order to do so.
```
msiexec.exe /i https://awscli.amazonaws.com/AWSCLIV2.msi
```
![Installing AWS CLI](asset/week%200%20installing%20aws.png)

AWS CLI successfullu configured
![Proof that AWS cli was successfully configured](asset/week%200%20aws%20configured.png)

### Create a billing alarm

I created a billing alarm so that I get notified when I go over budget. The alarm is set to a threshold of 1$.

![Billing alarm](asset/week%200%20billing%20alarm.png)
### Create budget

I created a budget using the AWS defualt set-up which sets the budget to 1$. 
I only set up one budget alarm because I do not want to go over the 2 budget free limit

![Imagine of the budget I created](asset/week%200%20budget.png)

### Recreated the logical arcihtectual diagram

![recreate the logical diagram](asset/Logical%20diagram.png)

[Lucid Charts share link](https://lucid.app/lucidchart/eff4c7ce-eab5-432c-ab41-0dd9be349a3a/edit?viewport_loc=-279%2C-31%2C3063%2C1239%2CN-gy0ho~jOyj&invitationId=inv_58e9a38a-888c-46e5-89c9-608a6c8acad1)

