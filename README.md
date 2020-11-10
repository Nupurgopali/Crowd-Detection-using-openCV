
# MOTIVATION
In the current pandemic situation to prevent the spread of CoronaVirus, Social distancing
is the need of the hour, but there have been violations in a lot of places. Even when the norms
have been implemented by the governments worldwide, people tend to not follow the rules. We
wanted to create a way for the local authorities to monitor the people breaking the social
distancing norms and take actions accordingly to control the spread of the virus.

# PROPOSED WORK
This is an efficient real-time deep learning based framework to automate the process of
monitoring the social distancing via object detection(YOLO) and tracking approaches, where each
individual is identified in the real-time using bounding boxes. The generated bounding
boxes aid in identifying the clusters or groups of people satisfying the closeness property
computed with the help of pairwise vectorized approach. The number of violations are confirmed
by computing the number of groups formed and violation index term computed as the ratio of the
number of people to the number of groups.Applying such technique helps overcome the
problem of false detection of moving groups and further prevents the activation of a false alarm.Then the data is sent to ubidots
platform wherethe data is monitored,in case of violation alert is sent and previously stored data are also 
analysed.
# TECHNICAL SPECIFICATIONS
1. OpenCV: Used to capture the video and perform image processing techniques and even
render the edited video .
2. Yolo object detection- Used to identify people in the video or in live streams.
3. IoT Platform(ubidots):This IoT platform is used to show the real-time data taken by the
model (in form of a dashboard)and even perform analysis over the previous datas
captured by the model.It is also used to send an alert in form of message and mail to the
concerned authorities when the crowd is detected in an area.

# RESULT
![image](https://user-images.githubusercontent.com/53776611/98709541-87843b00-23a8-11eb-8022-507be61f3db3.png)
![image](https://user-images.githubusercontent.com/53776611/98709612-a1258280-23a8-11eb-8d9a-8c13eaf8c492.png)
![image](https://user-images.githubusercontent.com/53776611/98709690-bac6ca00-23a8-11eb-843b-22bea834a18f.png)
