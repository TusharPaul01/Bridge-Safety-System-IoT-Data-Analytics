# Bridge-Safety-System-using-IoT (BSS)

BSS system uses sensors and micro-controllers to extract and pre-process data, visualize it in Google Collab, and use formulations to determine bridge overload.

Methodology:
Sensors like load sensors and IR sensors are present in the system. According to our algorithm, when a vehicle is detected by an IR sensor, the load sensor is triggered, thereby it fetches the data. This data is then transmitted to the ThingSpeak cloud, which serves as a centralized repository for storing and analyzing sensor data. Then we retrieve the data on a colab workspace, after that we pre-process the data & apply mathematical operations / checks. 
If the calculated weight exceeds the predefined threshold, our system triggers a notification on Colab, alerting us that the bridge is being overloaded. This notification enables us to take immediate action and prevent any potential damage or hazards associated with an overloaded bridge.
By employing this integrated approach, we can effectively monitor the weight of vehicles passing over the bridge in real-time, ensuring the safety and integrity of the structure. This system provides valuable insights into the load distribution and helps in making informed decisions regarding maintenance, load restrictions, or even potential upgrades to the bridge infrastructure to accommodate heavier loads in the future.

Steps :

1)Intall Arduino IDE on your system
2)Configure Arduino IDE set board type, baurd rate, COM port, etc.
3)Connect the sensors with micro-controller, according to the pins defined
4)Check & upload the code in micro-controller
5)Check the output on serial monitor
6)Create an acount on ThingsSpeak
7)Create a channel & generate API key
8)Enter all the details of ThingSpeak in the arduino code
9)Run the code again
10)Switch on the wifi & let the micro-controller connect to the wifi
11)Real-time data will be displayed on ThingSpeak & can be accessed anywhere through the link
12)Data pre-processing & data analysis portion is not provided here & it would be provide further.

-- Thank You --
