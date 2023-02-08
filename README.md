# EinsteinBot_Check_Agent_Availability_Flow

<h1>To check agent availability in the bot, we will create two flows.</h1>

a. <u>To check user presence status. We will use it as a subflow</u>

b. <u>To check agent availability</u>


<b>Reminder:</b> Ensure your permission set for bot is correct.

<h2> Step One:</h2>
<h2> Create an autolaunched Flow for 'Check User Presence Status' </h2>

![image](https://user-images.githubusercontent.com/37139091/217403205-f27b98c3-844b-4545-90d1-44452db7d465.png)

<h2>a. Get Records:</h2>

![image](https://user-images.githubusercontent.com/37139091/217404337-44a0dd62-0539-44b1-b3aa-7ae9956f49df.png)


<h2>b. Create a Decision to check if users were identified or not:</h2>

![image](https://user-images.githubusercontent.com/37139091/217404444-6214a2c1-bf17-4348-bad6-f64f6823127b.png)


c. ![image](https://user-images.githubusercontent.com/37139091/217404489-9408c1e5-a948-4dbf-a1d1-7d148d2bf33e.png)


<h2>d. Create an assignment if True:</h2>

![image](https://user-images.githubusercontent.com/37139091/217404570-70b6d380-b149-4cf4-bae6-178303db190e.png)




<h2> Step Two:</h2>


<h2> Create an autolaunched Flow for 'Checking Agent availability' </h2>

![image](https://user-images.githubusercontent.com/37139091/217405416-547ab0de-4ab6-467e-9483-29330e203ae3.png)



