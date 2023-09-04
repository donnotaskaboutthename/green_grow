# green_grow
 green grow is considered of the use of a feedback control system with Arduino Uno and various sensors successfully addressed challenges in Egypt's agricultural sector, resulting in a 6-fold increase in barley production, meeting sustainability and data collection goals, and outperforming existing solutions.
# Introduction
 In today's world, there are a number of grand challenges that we face as a society, from food scarcity to environmental degradation. To overcome these challenges, we need to improve the scientific and technological environment for all, increasing both the industrial and agricultural bases.
 In agriculture, one of the biggest challenges we face is how to sustainably produce enough food to feed our growing population while minimizing the negative impact on our environment. To address this issue, we present a feedback control system that utilizes the Arduino Uno to optimize plant growth by regulating temperature, humidity, moisture, and light. The agriculture industry faces numerous challenges, including climate change, limited resources, and a growing population. Climate change has led to extreme weather events, which in turn have had negative impacts on crop yields. the climate change has a bad impact on crop by the years increasing the number of events like droughts ,floods, and storms those are harmful to most of the crops. Limited resources, such as water and arable land, make it difficult to produce enough food to feed a growing population.
<img src="![image](https://github.com/donnotaskaboutthename/green_grow/assets/134716142/4978c9c5-7196-4520-8778-43adb19e9fe9)"width="500"hight="300">

 To address these challenges, there is a need for innovative solutions that can help increase crop yields while minimizing the negative impact on our environment. One of the earliest feedback control systems used in agriculture was the greenhouse, which was invented in the 19th century. Greenhouses provide a controlled environment for plant growth and protect crops from external environmental factors such as extreme weather events. By regulating temperature, humidity, and light, greenhouse producers can create optimal growing conditions for their crops, regardless of the external climate. Greenhouses have been widely adopted by farmers around the world and have proven to be an effective method of mitigating the negative effects of climate change on agriculture. However, greenhouses can be expensive to build and maintain, making them inaccessible to many farmers.
![image](https://github.com/donnotaskaboutthename/green_grow/assets/134716142/a693c757-7448-4af3-8cf1-4fd4aac89307)

To address the challenges faced by the agriculture industry, we set out to design a feedback control system that is sustainable, cost-effective, and easy to implement. Our system needed to have a long lifespan and be able to adapt to different environmental and economic conditions. We also needed to develop a method for mass production, so that our system could be easily replicated on a large scale. Finally, we needed to collect data from our system to track its performance and make any necessary adjustments. To address these requirements, we designed a feedback control system that utilizes the Arduino Uno to regulate temperature, humidity, moisture, and light for optimal plant growth. Our system incorporates a PC fan and an LED that produces heat to regulate the temperature of a confined setting. We used an LDR sensor to govern the amount of light that the plant is exposed to throughout the day, ensuring that it has access to light at all times. The temperature and moisture sensors provide the data required to regulate the input to the system. We also incorporated a small water pump connected to the Arduino to systematize periodic water droplets every five hours. 
Our feedback control system is sustainable and cost-effective, as it utilizes inexpensive and readily available components. The Arduino Uno is affordable and widely available, making it easy to implement, even for those with minimal programming expertise. We also incorporated a method for data collection by using an Excel sheet to track the measurable units from our project.
# Methods
  The development of our barley nursery prototype comprised three main stages.The first stage involved the creation of the hardware components, including the construction of the main body, the installation of the Arduino board, sensors, pumps, and all other necessary hardware components. During this stage, we installed TEC to stabilize our modified fans for cooling and warming our nursery, arranged the lights inside the body to optimize light distribution, and designed the water sprayer for efficient water division. The plastic body box (nursery) was then completed.
  
  ![Picture1](https://github.com/donnotaskaboutthename/green_grow/assets/134716142/53c5d133-16c5-4959-84be-676b26e8b436)
   
   In the second stage, we connected the sensors of DHT11 and LDR to the Arduino board to collect data on temperature, moisture, and light levels inside the nursery. The Arduino board was connected to two motor drivers and a relay to regulate the pumps, TEC fans, and two sprayers.
    
  ![image](https://github.com/donnotaskaboutthename/green_grow/assets/134716142/d339ed2f-7571-46c5-b7c1-4eb10aac905b)

  In the third stage, we created software code to control the hardware components. We first set up the DHT11 sensor library and defined our variables in the void setup beforewriting code pages for all necessary functions. These functions were then linked together in the void loop. An if statement was included to control the humidity and temperature; for instance, when the temperature exceeded 25 Celsius, the cooling fan would turn on until it reached 20 Celsius. Similarly, if the humidity dropped below 80%, the pump was activated until it reached 85%. The readings were monitored by the serial monitor and exported to Excel sheets to produce necessary data graphs. 
After completing the prototype, we conducted a five-day test plan to evaluate its performance. The prototype was powered up and loaded with barley. We recorded the weight of the barley before and after five days to ensure that it met our design requirement for mass production. The data collected was analyzed in Excel sheets to assess the prototype's performance, meeting our second design requirement. Finally, we calculated the energy consumption by the LDR to assess the prototype's sustainability and energy consumption, meeting our third design requirement. The previous efforts caused the difference in production between the sample in the barley nursery and the sample in the normal atmosphere.
# Result
  After constructing the prototype, we started to test our prototype to calculate mass production and energy consumption. We weighted the mass production by scale to calculate the difference in growth between the two Barley samples. Also, calculated the energy consumption theoretically by watt*time. The energy consumption by the LDR sensor from controlling the lights by turning it of 8 hours daily (the sunlight time) 25 watt*8 hours = 200 watts of energy saved per day. We made two test plans with two results.
  ![image](https://github.com/donnotaskaboutthename/green_grow/assets/134716142/29d9acc3-6502-4a3b-a5df-59890d18ee03)

   We solved the problems in the first test plan to get more great result, this problem wasn’t in our system it was in the way and steps of planting the barley. The solution is that we submerged the barley for 12 hours in the water before starting the planting process.
![image](https://github.com/donnotaskaboutthename/green_grow/assets/134716142/c05644f2-d2d7-49d1-83af-f86bd14ecac1)
  Generally, we solved the problems and increasing our project  good results by detecting the operation errors through feedback controlling system as shown in figure.
