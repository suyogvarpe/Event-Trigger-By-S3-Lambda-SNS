# Event-Trigger-By-S3-Lambda-SNS

This project is to create an event that triggers when any process occurs in an S3 bucket. I have implemented it using SNS (Simple Notification Service).

Steps to Create the Event:
1)Create an S3 bucket.
2)Create an SNS topic.
3)Create a subscription for this topic.
4)Confirm the subscription via the email you receive at your provided email address.
5)Create a Lambda function using the Blueprint option:
6)Select getObject for S3 event handling.
7)Select the bucket name.
8)Create a new role.
9)Add a destination to execute SNS:
10)Select SNS as the type of destination.
11)Open the S3 bucket and upload a document.
12)Once you upload a new document to the S3 bucket, you will receive a notification email at your subscribed email address.

Note: For reference, please check the attached screenshots.


