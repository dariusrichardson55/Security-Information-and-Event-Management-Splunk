<b><h1>Scheduling Reports & Alerts</h1></b>


First download Splunk (https://www.splunk.com/en_us/download/splunk-enterprise.html). Make sure to sign up and follow the instructions then sign in and then the page will redirect you to the download page to download Splunk.


 ![image](https://github.com/user-attachments/assets/e0f64dfe-7178-43dd-b774-d40668daf4f2)


Once downloaded, it will display the installer option, click the checkbox to licence agreement then press Next

![image](https://github.com/user-attachments/assets/adaed98a-459d-4194-b105-133dbfed2054)


Now you can just type in your username(the same as your email address that you used to sign up) and then your login password. Press next. Once you press next, click finish to automatically open Spunk Enterprise. 

![image](https://github.com/user-attachments/assets/862074f4-3ece-4024-b4c8-fcc1885a5894)



Sign in using your email address and password from your account.

![image](https://github.com/user-attachments/assets/7508a537-ae3b-4680-8f5f-9c46f84e5f18)

Once that’s done. Select Settings from the top, It will display a drop-down menu. Select Add data

![image](https://github.com/user-attachments/assets/46dd32fa-1c3a-4e76-a5ef-03e14fd8dccd)


Scroll down and select upload
![image](https://github.com/user-attachments/assets/af9dc651-560c-44e6-80e2-e8c5e14fc832)

Press select the file and upload the ‘sample_visualization_logs’ file then press next. Continue to press next until you reach the ‘done’ stage. 

![image](https://github.com/user-attachments/assets/d590cf69-da44-49d8-b25f-7e5e971baab0)

Next, press the start searching button.

![image](https://github.com/user-attachments/assets/4db99061-df50-4cad-9142-7548dee00fc8)

<b><h2>Creating a Report</h2></b>


Now we will save as a report for the data, to do so click the save as and then report.

![image](https://github.com/user-attachments/assets/ac532d66-5760-4df2-b94b-f3bf26328e31)

Name the report Threat Analysis and select 'No' for the time range picker.

![image](https://github.com/user-attachments/assets/81cde538-c6b4-48f2-8d53-a045cd34664b)

Then select a schedule to set when and how to be altered.

![image](https://github.com/user-attachments/assets/5cd2e5f3-8ae1-488b-9fb4-1fd85208206a)

Change the schedule to every week on Monday at 06:00 for the last 7 days. Schedule priority Higher 

![image](https://github.com/user-attachments/assets/d26cb16b-b177-405a-b84d-f0b9cf340205)

With the add actions button, you can select which action to take when the event has been triggered. Select Send email to be able to send the alert.

![image](https://github.com/user-attachments/assets/656f3aba-3382-425a-869a-71001d493966)

Enter the email address to which you want the alert to be sent.

![image](https://github.com/user-attachments/assets/028016f2-2157-4c32-bbac-ac3526324db6)

<b><h2>Create an alert</h2></b>

Go to save as and select alert.

![image](https://github.com/user-attachments/assets/6a735cf1-1491-4975-b73a-ce0610d8eb7c)

Enter the title and descriptions as well as select the real-time.

![image](https://github.com/user-attachments/assets/2c3e6eb8-0721-422e-aab1-0e69e53139b1)

On the pre-result option, select the ‘number of results’ button.

![image](https://github.com/user-attachments/assets/85c381bf-1342-4c18-b467-cc6ea5f2beb4)

In the add actions button, select ‘Add to triggered alerts’ then press save.

![image](https://github.com/user-attachments/assets/e8e676ee-5d86-4fc6-ba7e-679787270893)


Once that’s done. The result should be displayed below.

![image](https://github.com/user-attachments/assets/67d29798-a18a-419b-bc9a-99f9af1e5fe6)

This will display all the reports and alerts that you have saved.

![image](https://github.com/user-attachments/assets/554c0670-59c5-496d-95ec-129f40cc057a)


If click on the edit button on the report and click edit permissions, it will allow you to provide restrictions on how the user can access the report, such as read and write.

![image](https://github.com/user-attachments/assets/128e8b0b-86f2-4e08-bd8e-55d0f1acf303)














