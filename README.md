***********************
Cloudformation Project
***********************

*********************
Author: Jason Kelly
Student No. L00194486
*********************


This readme is to provide a guide on the steps taken to try and best complete the Lab Portfolio 1 project.

Steps:
1. Create Template in the Cloudformation section of the AWS Console

2. Add Description and Parameters to the Template
   - The description gives on overall view of what the template will create
   - The parameters include the environment name which will label all the resources when the stack is created
   - The parameters also include the CIDR blocks specifying the IP ranges to be used by the VPC,
     the Puclic and the Private Subnets.


3. Add the Resources
   - The resources need to be added and configured correctly in order for the stack to work
   - The resources were added in the following order
   i)    VPC
   ii)   Internet Gateway and VPC Internet Gateway Attachment
   iii)  Public and Private Subnet
   iv)   The NAT Gateway and Elastic IP
   v)    The Public Route, Public Route Table and Public Route Table Association
   vi)   The Private Route, Private Route Table and Private Route Table Association
   vii)  The Security groups for the Public Facing Instance and Private Instance
   iix)  The SSH Key Pairs to allow access to the EC2 instances
   ix)   The Public and Private Instance

4. Add the Outputs
   - The outputs show in the AWS stack creation console what was created

5. After template has been customised, the template is then vaildated

6. Once the template is validated it can be created

7. Verify the Stack was created without errors

8. Once the stack has been successfully created verify all the resources have been created

9. If all the resources were created successfully the User should be able to access the Public Facing EC2

10. From the Public facing EC2 instance the User should be able to access the Private EC2 Instance


