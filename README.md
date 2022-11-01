# Engineering-FY-Project-
This repository contains the deocumentation of my final year project.

## Note:
Kindly ensure you strictly use this report as a reference <b>ONLY</b>. We have published a paper in <b>2022 IEEE International Conference on Electronics, Computing and Communication Technologies (CONECCT)</b>
Link for paper: https://ieeexplore.ieee.org/document/9865823

### Abstract
58% of India’s population relies on agriculture to earn their living. In view of this, farmers contribute most to the Indian economy among many other professions. While technology evolves, the agricultural sector still follows ad-hoc procedures and is yet to be digitised. Starting from sowing seeds, maintenance of the crops and timely watering of the crops are some of the essential tasks among many others. This paves way for technology to help and support farmers to perform their tasks smartly and help them focus on tasks that require human intervention. Technologies like IoT, AI/ML, and Server-End technologies can essentially help in creating a pipeline of streamlined processes that are reliable and convenient to farmers. These technologies help build an ecosystem of smart processes which ultimately makes farming an easier occupation and less prone to risks.

We have built an android application and a front end application that enables farmers and other users to go through the different stats of the sensors on the field. The android application enables the farmers to remotely monitor the statuses of different factors such as the amount of Nitrogen, Phosphorus, and Potassium in the soil, the humidity in the air, moisture in the soil among other factors. The app is also capable of performing disease detection for tomato and potato plants. The front end application that we have built represents real time values for the temperature and also predicts the prices of tomatoes and potatoes based on the values present on the dataset.

### Existing System
Currently, there are a lot of systems present in the world that already bring about automatic seeding. While these systems are effective, they are not efficient enough. Seeding happens at the start of every season to grow a particular crop. Each crop has its differences in terms of soil conditions, moisture content, and nutrient necessity. Some crops would require seeding at a more frequent rate as compared to others.

In such scenarios, these automatic seeding machines may render useless once the seeding is done for a particular crop. After that duration, it just remains idle with nothing else to do. There are a lot of systems that deal with measuring soil quality, moisture content, and other conditions. But, all these systems work in silo i.e. Independently. This is a major cause of inefficiency.

### Proposed System
Our proposed system tries to provide precision farming utilities using the latest technologies. Precision farming utilities include incorporating IoT sensors to get readings of metrics such as soil moisture level, temperature, NPK (Nitrogen-Phosphorus-Potassium) levels, soil oxygen level, etc. These readings are made remotely accessible to the farmer. Our proposed system does the following-

● Store sensor data on GraphCMS
● Create a browser-based dashboard web-application using Next.JS and React.JS
● Create another dashboard for Android mobile phones
● User can remotely access sensor data and metrics and receive alerts
● Query data more efficiently using GraphQL
● Predict market prices and market arrival of crops using past data and train a model using which the
future prices and arrival could be predicted.
● The data collected from the sensors could be used to train a DL model using the time forecasting
techniques to predict future variabilities.
