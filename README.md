# EinsteinBot_Check_Agent_Availability_Flow
<b>POC</b>

<h1>To check agent availability in the bot, we will create two flows.</h1>

a. <u>To check user presence status. We will use it as a subflow</u>

b. <u>To check agent availability</u>


<b>Reminder:</b> Ensure your permission set for bot is correct.

<h2> Step One:</h2>
<h2> Create an autolaunched Flow for 'Check User Presence Status' </h2>

![image](https://user-images.githubusercontent.com/37139091/217403205-f27b98c3-844b-4545-90d1-44452db7d465.png)

<h2>a. Get Records:</h2>

![image](https://user-images.githubusercontent.com/37139091/217404337-44a0dd62-0539-44b1-b3aa-7ae9956f49df.png)


<h2>b. Create a Decision to Check If Users Were Identified Or Not:</h2>

![image](https://user-images.githubusercontent.com/37139091/217404444-6214a2c1-bf17-4348-bad6-f64f6823127b.png)


c. ![image](https://user-images.githubusercontent.com/37139091/217404489-9408c1e5-a948-4dbf-a1d1-7d148d2bf33e.png)


<h2>d. Create An Assignment If True:</h2>

![image](https://user-images.githubusercontent.com/37139091/217404570-70b6d380-b149-4cf4-bae6-178303db190e.png)




<h2> Step Two:</h2>


<h2> Create An Autolaunched Flow for 'Checking Agent availability' </h2>

![image](https://user-images.githubusercontent.com/37139091/217405416-547ab0de-4ab6-467e-9483-29330e203ae3.png)

<h2>a. Get Records of Users Assigned to an Queue: </h2>

![image](https://user-images.githubusercontent.com/37139091/217405739-68c38c67-9f0c-4da9-bf1f-300c68dc5039.png)

![image](https://user-images.githubusercontent.com/37139091/217405979-991f130f-3650-4749-8d1f-cfbd93622040.png)


<h2>b. Loop Through a Collection Of Group Members Users: </h2>

![image](https://user-images.githubusercontent.com/37139091/217406122-32558b5e-598b-4e06-bc92-bdbabe6a85a5.png)

<h2>c. Call The Subflow We Created Previously - Check User Presence Status: </h2>

![image](https://user-images.githubusercontent.com/37139091/217406285-29962dce-34dc-4524-ab7f-3c83f007e3c8.png)

<h2>d. Create a Decision To Check Each Agent Availability: </h2>

![image](https://user-images.githubusercontent.com/37139091/217406777-ba881d21-6534-4205-a6ef-dd4637d0eca9.png)

![image](https://user-images.githubusercontent.com/37139091/217406840-b0d6d548-0a7d-475e-b53b-c09ba3c02375.png)


<h2>e. Create An Assignment Where there Is At Least One Agent Available: </h2>

![image](https://user-images.githubusercontent.com/37139091/217406962-afcda453-ca26-44b9-8448-5c40877c4b59.png)


<h2> Step Three - In Bot:</h2>

<h2>a. Create a dialog called 'chat with live agent'. In this dialog, you will view the Apex code we worked on </h2>
<h2> </h2>
<h2> </h2>
<h2> </h2>
<h2> </h2>




