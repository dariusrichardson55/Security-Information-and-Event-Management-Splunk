<h1>Description</h1>
This task provides an example of creating a dashboard on Splunk to be able to easily access specific up-to-date data without
needing to search queries every time to locate data.

<h1>Website</h1>

This is the website used for the duration of the task.

<ul>
<li><a href="https://prd-p-dwdc9.splunkcloud.com/en-GB/account/login?return_to=%2Fen-GB%2Faccount%2F">Splunk Cloud Platform</a></li></ul>

<h1>File</h1>

This CSV file will be used to add the data to the Splunk Cloud Platform.

<ul>
  <li>splunk_sample_data.csv</li>
</ul>

<b><h1>Task walk-through</h1></b>

<p align="center">First, go to settings and press 'Add data'.</p>

![image](https://github.com/user-attachments/assets/cb73b721-299d-464d-b44a-09af9aa0fb01)

<p align="center">Press upload to get the splunk_sample_data.csv.</p>

![image](https://github.com/user-attachments/assets/7f179717-0393-4e47-9602-17d79459d508)

<p align="center">Once uploaded, continue to press next until you reach done.</p>

![image](https://github.com/user-attachments/assets/311c653a-64f6-48bf-bfe1-5a5f4b513ed2)

<p align="center">When reaching the 'Done'stage, press 'Build Dashboards'.</p>

![image](https://github.com/user-attachments/assets/dde6407d-933c-4ade-8a5a-0cad8916e819)

<p align="center">Next, press 'Create New Dashboard'.</p>

![image](https://github.com/user-attachments/assets/70ca1815-b076-4d9a-83a8-2331f2f2b47a)

<p align="center">Name the dashboard 'Login attempts dashboard' and select classic dashboards. Click on the 'create' button.</p>

![image](https://github.com/user-attachments/assets/05c1cbd7-d5d1-4aca-97a3-7a6b894d377d)

<p align="center">Press 'Add panel' then select 'columns'. On the time range change the 'Last 24 hours' to 'All time'.</p>

![image](https://github.com/user-attachments/assets/5d07e757-793a-471f-b55f-94a37e9e93c8)

<p align="center">Put the Content Title as 'Failed login attempts' and event_type="login_failed" status="failure" in
the Search String. This query will gather all data that has login_failed as the event_type and failure as the status, then press add new dashboard.</p>

![image](https://github.com/user-attachments/assets/9d9d7afe-8066-459c-b9d4-9a1230587517)

<p align="center">Press 'Add panel' then select 'columns'. On the time range change the 'Last 24 hours' to 'All time'.</p>

![image](https://github.com/user-attachments/assets/87acc0a5-1e6b-4d10-a2ed-4685d0c2984e)

<p align="center">Put the Content Title as 'Failed login attempts'and put event_type="login_successful" status="success" in
the Search String. This query will gather all data that has login_successful as the event_type and success as the status.</p>


![image](https://github.com/user-attachments/assets/1da4ce64-7779-4b44-a652-2803feeac250)

<p align="center">It should display two-column charts showing the number of failed login attempts and the number of successful login attempts.</p>

![image](https://github.com/user-attachments/assets/3b35fe87-1efa-4614-a9eb-5eecac1043ce)
