The lab in 4.3 goes over how to create a billing alarm.
This file will contains any notes I take on the process

Billing Alarm - will send you an alert when your bill for the month goes over a set amount.

1. Go to CloudWatch in the console
2. Go to billing
3. Create alarm

Period is how often the system will check the cost.
4. Createe a new SNS topic: throw in a legitimate email address, click create
5. Go to your email to subscribe to the topic
6. Next in the console, name the alarm and put in a description

Pending confirmation means you have not gone to your meail yet.
After confirming, you can can go back to the console, hit refresh and the message should change.

CERT:
If the exam asks how you can get automatic notifcations if the account goes over a cost threshold, the answer will have to do with creating a billing alarm.