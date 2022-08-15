# PGProject

Deep Learning for Histology of Onchocerciasis

This repo contains the code for my MSc research work on Deep Learning for Histology of Onchocerciasis. The dataset can be downloaded from http://vislab.isr.ist.utl.pt/datasets/

Platform: AWS Sagemaker

Language: Python

DL framework: Pytorch

Additional packages used:

MMCV


The original dataset can be downloaded from the link given above.
The folder contains interactive python notebooks with their outputs.


Setting up SageMaker 

1. To onboard to the Domain using Quick setup

2. Open the SageMaker console.

3. Choose Control Panel at the top left of the page.

4. On the Setup SageMaker Domain page, choose Quick setup.

5. Under User profile, for Name keep the default name or create a new name. The name can be up to 63 characters. Valid characters: A-Z, a-z, 0-9, and - (hyphen).

6. For Default execution role, choose an option from the role selector. This is the default role that is assigned to the Amazon SageMaker Domain user profile.

7. If you choose Enter a custom IAM role ARN, the role must have at a minimum, an attached trust policy that grants SageMaker permission to assume the role. For more information, see SageMaker Roles.

8. If you choose Create a new role, the Create an IAM role dialog opens:

9. For S3 buckets you specify, specify additional S3 buckets that users of your notebooks can access. If you don't want to add access to more buckets, choose None.

10. Choose Create role. SageMaker creates a new IAM AmazonSageMaker-ExecutionPolicy role with the AmazonSageMakerFullAccess policy attached.

11. Choose Submit.

12. From the pop-up window, select a Amazon Virtual Private Cloud (Amazon VPC) and subnet to use.

13. Choose Save and continue.

Note
If you receive an error message that you need to create a VPC, see Choose a VPC.

14. When Status is Ready, the user name that you specified is enabled and chosen. The Add user and Delete user buttons, and the Launch app link are also enabled.

15. From Launch app, select Studio. The Amazon SageMaker Studio loading page displays.

16. When Studio opens, you can start using it.

Now that you've onboarded to SageMaker Studio, use the following steps to access Studio later.

To access Studio after you onboard

1. Open the SageMaker console.

2. Choose Control Panel at the top left of the page.

3. On the Control Panel, choose your user name and then choose Launch app. Select Studio.

4. To add more users

5. On the Control Panel, choose Add user.

6. Repeat steps 4 and 5 from the first procedure, "To onboard to Amazon SageMaker Domain using Quick setup."

7. Choose Submit.
