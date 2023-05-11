# Andriod-GPS-Location-Bluetooth-Broadcast
An Android Application Built to send GPS location data to a bluetooth receiver. This data was used as ground truth for statistical analysis for a dead reckoning system.

This was developed and tested using a Google Pixel 6a.The app requires the phone’s bluetooth feature and acts as a bluetooth client. In addition to the app, our team created a Bluetooth Server using Python to obtain from the phone bluetooth client. Now, this app allows us to obtain real-time GPS data as well as allows users to select the frequency of the GPS that will be collected.

<img width="877" alt="Figure 1" src="https://github.com/JonathanSwindell/Andriod-GPS-Location-Bluetooth-Broadcast/assets/15970270/45e4242b-93f7-455e-8bd4-c0b96fc97952">


<img width="843" alt="Figure 2" src="https://github.com/JonathanSwindell/Andriod-GPS-Location-Bluetooth-Broadcast/assets/15970270/09b3738f-ded8-4237-841c-de8e3701152e">

An implementation of the server side receiver code can be found here https://github.com/JonathanSwindell/Dead-Reckoning-Subsystem-for-a-Multi-Sensor-Fusion-Localization-System-/blob/main/ros_workspace/src/navigation/scripts/GPS_Bluetooth.py.
