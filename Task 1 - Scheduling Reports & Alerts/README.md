<h1>Description</h1>
This task provides an example of how to schedule a report that is scheduled
to run and to set an alert when a condition is met.


<h1>Website</h1>

This is the website used for the duration of the task.

<ul>
<li><a href="https://prd-p-dwdc9.splunkcloud.com/en-GB/account/login?return_to=%2Fen-GB%2Faccount%2F">Splunk Cloud Platform</a></li>

</ul>

<h1>File</h1>

This CSV file will be used to add the data Splunk Cloud Platform. 

<ul>
  <li>sample_visualization_logs.csv</li>
</ul>

<b><h1>Task walk-through</h1></b>

<p align="center">First download Splunk (https://www.splunk.com/en_us/download/splunk-enterprise.html). Make sure to sign up and follow the instructions then sign in and then the page will redirect you to the download page to download Splunk.</p>

![image](https://github.com/user-attachments/assets/4652724f-6726-428d-ba3b-fe777df0bce4)


<p align="center">Once downloaded, it will display the installer option, click the checkbox to licence agreement then press Next.</p>

![image](https://github.com/user-attachments/assets/adaed98a-459d-4194-b105-133dbfed2054)

<p align="center">Now you can just type in your username(the same as your email address that you used to sign up) and then your login password. Press next. Once you press next, click finish to automatically open Spunk Enterprise.</p> 

![image](https://github.com/user-attachments/assets/862074f4-3ece-4024-b4c8-fcc1885a5894)



<p align="center">Sign in using your email address and password from your account.</p>

![image](https://github.com/user-attachments/assets/7508a537-ae3b-4680-8f5f-9c46f84e5f18)

<p align="center">Once that’s done. Select Settings from the top, It will display a drop-down menu select Add data.</p>

![image](https://github.com/user-attachments/assets/c5714662-42bf-4741-89d9-61402fde0070)


<p align="center">Scroll down and select upload.</p>

![image](https://github.com/user-attachments/assets/07416312-68c9-4855-b18e-2f53f64cbbf3)


<p align="center">Press select the file and upload the ‘sample_visualization_logs’ file then press next. Continue to press next until you reach the ‘done’ stage.</p> 

![image](https://github.com/user-attachments/assets/0691ac48-e9ca-473d-a823-e04c3eb22637)


<p align="center">Next, press the start searching button.</p>

![image](https://github.com/user-attachments/assets/4db99061-df50-4cad-9142-7548dee00fc8)

<b><h2>Creating a Report</h2></b>


<p align="center">Now we will save as a report for the data, to do so click the save as and then report.</p>

![image](https://github.com/user-attachments/assets/ac532d66-5760-4df2-b94b-f3bf26328e31)

<p align="center">Name the report Threat Analysis and select 'No' for the time range picker.</p>

![image](https://github.com/user-attachments/assets/81cde538-c6b4-48f2-8d53-a045cd34664b)

<p align="center">Then select a schedule to set when and how to be altered.</p>

![image](https://github.com/user-attachments/assets/a5c19ae0-2631-4830-b193-6d39801f20ee)


<p align="center">Change the schedule to every week on Monday at 06:00 for the last 7 days. Schedule priority Higher.</p> 

![image](https://github.com/user-attachments/assets/d26cb16b-b177-405a-b84d-f0b9cf340205)

<p align="center">With the add actions button, you can select which action to take when the event has been triggered. Select Send email to send the alert.</p>

![image](https://github.com/user-attachments/assets/1a177877-33e5-4a56-b681-12eb1e0e14d4)


<p align="center">Enter the email address to which you want the alert to be sent.</p>

![image](https://github.com/user-attachments/assets/028016f2-2157-4c32-bbac-ac3526324db6)

<b><h2>Create an alert</h2></b>

<p align="center">Go to save as and select alert.</p>

![image](https://github.com/user-attachments/assets/a3ff5810-d028-41a5-b3eb-29db47ebbb91)


<p align="center">Enter the title and descriptions as well as select the real-time.</p>

![image](https://github.com/user-attachments/assets/2c3e6eb8-0721-422e-aab1-0e69e53139b1)

<p align="center">On the pre-result option, select the ‘number of results’ button.</p>

![image](https://github.com/user-attachments/assets/5cf478ef-c146-4957-b26a-469fdbd20e2a)


<p align="center">In the add actions button, select ‘Add to triggered alerts’ then press save.</p>

![image](https://github.com/user-attachments/assets/bf817c6f-53ff-4598-ab37-9863d1895d99)


<p align="center">Once that’s done. The result should be displayed below.</p>

![image](https://github.com/user-attachments/assets/67d29798-a18a-419b-bc9a-99f9af1e5fe6)

<p align="center">This will display all the reports and alerts that you have saved.</p>

![image](https://github.com/user-attachments/assets/554c0670-59c5-496d-95ec-129f40cc057a)


<p align="center">If click on the edit button on the report and click edit permissions, it will allow you to provide restrictions on how the user can access the report, such as read and write.</p>

![image](https://github.com/user-attachments/assets/128e8b0b-86f2-4e08-bd8e-55d0f1acf303)
