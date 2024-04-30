# IoT Based Accident Detection and Alert System
![Prototype_1](https://github.com/Shadrackssien/IoT-Based-Accident-Detection/assets/117119351/83b5013c-0765-4a48-8736-65ab4a76f005)

Lack of prompt assistance as a result of the time it took to get accurate location information is the most evident reason why someone dies in an accident. The police or the rescue squad are typically not notified in time when a road accident happens. Many times when an accident happens at night and the victim is unconscious, it will take hours for someone to discover the situation and call the police. Therefore, saving that valuable time will save lives. The risk of mortality for the victim is further increased by the time it takes the rescue team to get to the accident scene and by the high traffic between the accident site and the hospital facilities.
<br/>
Therefore, an IoT-based accident detection and alarm system must be created and put into place to save victims quickly and lower the probability of fatalities from traffic accidents. This System uses both an accelerometer and vibration Sensor to communicate the data via SMS to the closest police and ambulance 
service and coupled to a GPS and GSM module.

## System Architecture

The system's design and features are split into three stages, which include;
<br/>
i. Accident Detection: As the controlling unit, Arduino UNO communicates with the modules to improve 
information transformation over time. The Vibration sensor is used to detect 
vibrations following an increase in threshold voltage and detect collisions. When a vehicle 
is thrown over in any direction along the X, Y, or Z axes, an accelerometer sensor detects 
the accident. The vehicle's tilt can be adjusted from zero degrees at rest to 360 degrees in 
any direction. The accelerometer interprets the scenario as an accident if the angle of the 
moving object rises above our threshold value in any direction. The X and Y axes' respective 
threshold values are 310 and 340. The sensor will alert the microcontroller if an accident is 
discovered. Additionally, a buzzer is given to notify other motorists about the collision and 
request their assistance.
<br/>

ii. Location Tracking: The GPS sensor can determine the location of the car. The GPS device is used in our 
suggested technique to determine the precise accident location. The microcontroller requests the GPS to provide the precise position of the accident scene whenever it notices any hint of an accident. The GPS transmits the accident site's location to the microcontroller.
<br/>

iii. Notification Sending: GSM sends a text message to the hospital and police control center using the accident 
location link. A message including the precise location's latitude and longitude will be sent 
to the police control center, hospital, and map link. A notice informing users about the 
incident and providing a link to a Google map is sent at the same time to the closest police 
station. These specifics allow the ambulance to travel the quickest path to the scene of the 
accident and shorten the time it takes to save the victims' lives. In case of a false alarm, there 
is a push button that the user can press to disallow sending messages to the police and 
ambulance service. 
<br/>

### System Components
The hardware components selected for the system are:
i. Arduino microcontroller; 
ii. LCD Display;
iii. GPS Module;
iv. GSM Module;
v. Buzzer;
vi. Jumper Wires
vii. Accelerometer
viii. Vibration Sensor

### Demonstration and Prototypes

https://github.com/Shadrackssien/IoT-Based-Accident-Detection/assets/117119351/087ba7b1-0438-41ab-9d5e-61a5ec81ba4a
![prototype_2](https://github.com/Shadrackssien/IoT-Based-Accident-Detection/assets/117119351/bb2b85a2-8c42-4b2b-aa76-be3b14a2da24)

![code-screenshot](https://github.com/Shadrackssien/IoT-Based-Accident-Detection/assets/117119351/b4f159d5-8ba4-4b10-b0e5-f7c82533194b)

## Download The pdf file [here](https://drive.google.com/file/d/1I3UXLrcjZlZDK8OALrGgq3kUarrcsQNX/view?usp=sharing)

