## WORKING WITH EBS

### NAME: R.TEJASWINI
### REGISTER NO:212224230218
## AIM:

In this lab environment, access to AWS services and service actions might be restricted to the ones that are needed to complete the lab instructions. You might encounter errors if you attempt to access other services or perform actions beyond the ones that are described in this lab.

## OBJECTIVE:

*Create an Amazon EBS volume
*Attach and mount your volume to an EC2 instance
*Create a snapshot of your volume
*Create a new volume from your snapshot
*Attach and mount the new volume to your EC2 instance

## Illustration:

# STEP 1:
In this step, you will create and attach an Amazon EBS volume to a new Amazon EC2 instance.You will see an existing volume that is being used by the Amazon EC2 instance. This volume has a size of 8 GiB, which makes it easy to distinguish from the volume you will create next, which will be 1 GiB in size.

<img width="1542" height="736" alt="image" src="https://github.com/user-attachments/assets/cd7beef9-861a-4511-a57c-cbaf82f9255e" />

<img width="942" height="880" alt="image" src="https://github.com/user-attachments/assets/4b0398bc-4246-4d7f-8d22-a446d344b568" />

# STEP 2:
In this step, you will connect to the Lab EC2 instance using Session Manager.You can now attach your new volume to the Amazon EC2 instance.

<img width="948" height="880" alt="image" src="https://github.com/user-attachments/assets/9d246b2f-56e8-4b2b-af35-44a9b343731c" />

# STEP 3:
In this step, you will add the new volume to a Linux instance as an ext3 file system under the /mnt/data-store mount point.

<img width="954" height="878" alt="image" src="https://github.com/user-attachments/assets/d3fab652-842a-435e-b669-1595c636c512" />
<img width="957" height="1078" alt="image" src="https://github.com/user-attachments/assets/095ba2cb-4e7c-44ab-9126-6e8924286359" />
<img width="961" height="1078" alt="image" src="https://github.com/user-attachments/assets/c2f3d615-1745-4d6f-9d0e-1abf4c7179c3" />

# STEP 4:
You can create any number of point-in-time, consistent snapshots from Amazon EBS volumes at any time. Amazon EBS snapshots are stored in Amazon S3 with high durability. New Amazon EBS volumes can be created out of snapshots for cloning or restoring backups. Amazon EBS snapshots can also be easily shared among AWS users or copied over AWS regions.

<img width="954" height="878" alt="image" src="https://github.com/user-attachments/assets/e18a5014-4041-415c-935c-2b48638f30fb" />
<img width="960" height="876" alt="image" src="https://github.com/user-attachments/assets/434dec9a-b3c4-4545-ad56-f8a9d5e9611b" />

# STEP 5:
<img width="603" height="527" alt="image" src="https://github.com/user-attachments/assets/4c447805-3d63-4de5-a9e6-33ce6e4f0c2c" />

## RESULT:
Successfully created, managed, and deleted an EBS bucket on AWS, demonstrating the ability to upload, access, and control objects within Amazon EBS.

