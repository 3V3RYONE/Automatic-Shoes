# Automatic-Shoes
This Repository contains the Arduino code for Automatic Shoes project.  
    
# Algorithm
The algorithm for this code is simple. We have an ultrasonic sensor, an Arduino, a relay module and a motor. 
The code calculates the distance of an obstruction detected by the ultrasonic sensor.  
If that distance is lesser than 50 cms, the Arduino sends a LOW signal to the relay module.  
This LOW signal breaks the Normally Closed connection of the relay module with the motor and the motor stops. Hence, the Shoes stops.  
  
# Connections
Trig pin of sensor - 12th pin of Arduino
Echo pin of sensor - 13th pin of Arduino
Relay module's input pin - 8th pin of Arduino
Relay module and motor connected with Normally Closed condition.  
  
# Output
The shoes runs smoothly when pressed ON. When an obstruction is detected in the specified distance, the Shoes stop automatically until the obstruction is cleared off the path.
