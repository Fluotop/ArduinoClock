# ArduinoClock
Wifi based electronic clock: using an ESP-01 wifi module sending the current time to an ATMEGA-8 microcontroller (one controlling each segment). ATMEGA's convert recieved time into motor commands which are stored into 74HC595 shift registers (4 per digit). Motor commands are recieved by UCM301 driver boards (1 per motor) which generate the turning instructions for the 28BYJ-48 stepper motor. 
# Electronic schema
![IMG_20220619_214446](https://user-images.githubusercontent.com/61277099/232130089-2f3eb9da-3693-4c55-9bc4-dd718a9095dd.jpg)
# Breadboard testing of a single segment (digit)
![IMG_20220522_211205](https://user-images.githubusercontent.com/61277099/232129897-93133422-5529-4a08-86b6-daed37430bd8.jpg)
# PCB schema
![IMG_20220619_214500](https://user-images.githubusercontent.com/61277099/232130142-8ab4da17-9103-46d7-869b-8991f7df9b3e.jpg)
# Printed PCB
![IMG_20220709_161107](https://user-images.githubusercontent.com/61277099/232129827-64cf0a1a-9bee-4d13-bfa6-35972cfc4edd.jpg)
# Mounting comnponents on board
![IMG_20221023_103744](https://user-images.githubusercontent.com/61277099/232129865-405a549c-0d33-4236-a2b1-c9fe2e4050a3.jpg)
# Model of 3D segments to be printed
![IMG_20220828_191812](https://user-images.githubusercontent.com/61277099/232129848-3fe667f9-596d-4882-b6a7-e5e2919ad861.jpg)
# Final result
![Naamloos](https://user-images.githubusercontent.com/61277099/232129876-17d2e286-548d-4a64-a780-412725576ba6.png)

