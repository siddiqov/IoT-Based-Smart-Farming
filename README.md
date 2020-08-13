# IoT-Based-Smart-Farming
A short description of Smart Farming based on IoT. 
The main focus is IoT infrastructure here that can be used in other context 
Requirement:
1- Windows 10 working as a gateway (In Future RPi will be used)
2- An Xbee coordinator attached to the gateway
3- Xbee router with same netwrok ID for edge layer.
3- Thingspeak cloud is used. An account has to be created that will provide writing and reading keys speratley and a channel ID.
4- Replace above credential with yours one in a function name my_main() in file "IoT_Based_Smart_Farming_Main.ipynb".
5- Create an account in RabbitMQ "https://www.rabbitmq.com/"
Place the entire folder of IoT_Gateway in a default workspace of anacodna environment e.g in my case, the folder path is "C:\Users\Dell\Workspace\IoT_Gateway".
Open the Anaconda Navigator and a file named "IoT_Based_Smart_Farming_Main.ipynb" from IoT_Gateway folder
