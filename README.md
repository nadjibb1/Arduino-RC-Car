# Arduino-RC-Car 
In this project, I developed an RC car using Arduino Uno, equipped with Bluetooth connectivity to switch between different operational modes: manual control, obstacle avoidance, and line following.
The car has 2 dc motors to move controlled by L298 Driver.
The car featured an HC-05 Bluetooth module for wireless communication, allowing users to control the car via a smartphone app.
In manual mode, users could directly control the car’s movements.
The obstacle avoidance mode utilized ultrasonic sensors to detect and navigate around obstacles autonomously. 
The line follower mode employed infrared sensors to track and follow a predefined path.
# Hardware connections
Bleutooth: RX pin D2 / TX pin D3.<br>
Right IR Sensor: pin A0 / Left IR Sensor: pin A1.<br>
UltraSonic Sensor: Echo pin A2 / Trigger pin A3.<br>
Servo Motor pin A4.<br>
L298 Pin enA to pin 10<br>
L298 Pin in1 to pin D9<br>
L298 Pin in2 to pin D8<br>
L298 Pin in3 to pin D7<br>
L298 Pin in4 to pin D6<br>
L298 Pin enB to pin D5
