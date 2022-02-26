# Week-2-Industrial-IoT-with-Google-Cloud-Quiz
Week 2

What is IoT?

Quiz-1: Internet of Things use cases

1. Take a moment to ponder some of the uses of IoT: predictive maintenance, industry safety solutions, building and home automation, remote patient monitoring, asset tracking, and fraud detection. 

Ans: All the use cases are gaining real time or near-real time insights about an environment that cannot be obtained any other way.


2. Why has IoT become so popular in the last few years? 

Ans: Better cloud IoT architectures and integrated data analysis tools have led to more insights from IoT data.


3. Which of the following characteristics are crucial for an IoT network? (Choose TWO)

Ans: An IoT network must be capable of scaling quickly.
     An IoT network must be able to process and store data quickly.


Quiz 2: IoT networks

1. What functions can be performed by an IoT gateway? Choose THREE.

Ans: Perform real-time analytics
     Perform machine learning
     Connect devices to the cloud


2. What makes IoT data valuable? 

Ans: The data can give insights into real world situations.


3. A delivery company wants to add localization intelligence to its IoT network. It has 1000 drivers and trucks, but in the next few years it wants to add self-driving trucks. 
As it is designing its network, what are some things that its IoT network designers should keep in mind? Choose TWO.

Ans: The risk of creating a communication bottleneck when adding the self-driving trucks.
     Connecting a new generation of devices into an exixting IoT network.


4. An IoT network is used to predict electricity usage in a smart city. The network has one million devices sending data to the cloud. The network designers have added predictive usage to the network. Which means, depending upon the usage predictions, the network will turn off air conditioning and lights in low use buildings.
Initial tests of the network are showing the bottlenecks in data processing. What could the designers do to fix this problem?

Ans: Move the prediction tasks from the cloud to the edge. 



Cloud IoT Platform

Quiz 1: Ingest, Process, Analyze

1. You are designing an IoT network to monitor hallway activity at the local college. Whenever there is movement in the hallway, you will want to track it to determine lighting, temperature, and classroom use. 
What assumptions can you make while developing your network? Choose TWO.

Ans: Data will arrive in bursts with periods of low or no activity as well as periods of high activity.
     To train a model to predict activity, you will need data over several semesters. 


2. You are designing an IoT network that monitors hallway activity in all schools in New York city.
 What assumptions can you make while developing your network? Choose TWO.

Ans: Massive amounts of data need to be stored. The network needs inexpensive storage capacity with fast access to recent data as well as access to older data. 
     During periods of high activity messages may come into the network at the same time, potentially leading to data loss. To prevent this you will need a system that can guarantee message delivery. 


3. You have successfully designed an IoT network for a school district. You have also created a machine learning model that makes inferences about student activity in the hallways. 
What considerations should you keep in mind as you deploy your network? Choose ALL that apply.

Ans: The machine learning model will need to be regularly trained with new data. 
     You will have to keep track of changes in the holiday schedules for the schools, as this can affect the ML model. 
     If the number of schools and students increase, it may be necessary to consider doing some of the data processing on the Edge, rather than in the cloud. 



Quiz 2: Google Cloud IoT Characteristics

1.Why is being serverless an important characteristic of Cloud IoT?

Ans: Being serverless means the cloud network can expand and contract to meet the variable needs of IoT. 


2. You are designing an IoT network of 1000 devices. It is critical to know when a device is offline. You want to know as soon as possible that a device is not communicating with the cloud. 
What should you do to make this possible?

Ans: When creating the devices add the Cloud Logging feature to the device. Set the monitoring at Error level to capture failed connection attempts and communication errors. 


3. Why would intelligence built-in with ML and AI capabilities be of great interest to IoT?

Ans: ML and AI can generate a lot of insights from IoT data, making that data more valuable. 


4. What are the advantages of ML on the Edge? (Choose TWO)

Ans: Doing ML on the Edge decreases latency
     Doing ML on the Edge increases privacy by keeping data on the device


5. You are designing an IoT network with 1000 devices located all over Tasmania. They will be in areas open to the public. 
What security measure should you use to stop or minimize an attack?

Ans: Each device should have a unique authorization key. 



