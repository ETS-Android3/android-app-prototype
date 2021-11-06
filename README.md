# Open Source Project; early contributions by Raúl Gómez Acuña (thank you; open source respect)
# Further contributions by Asper Technologies engineering team 

# heart-rate-monitor
Asper Tech Android prototype, composed of an Android and Web applications working together as a whole.

The Android application acts as a bridge, providing an interface to connect your personal heart rate commercial sensor through Bluetooth 4.0 Low Energy. The application will receive data from the sensor and will parse it appropriately, in order to transfer it to a web server by HTTP POST requests. It will also send location information periodically to track down the user.

The web server will communicate with the browser via Web Socket connection so as to send real-time heart rate and location values.

The web client will be able to monitor those values as well as showing a graph with the latest heart rate samples. It will also allow the user to view the current location of the person being monitored.

Notification system included to notify via email when certain heart rate conditions take place.

MongoDB implemented to store every heart rate sample received and hence making possible data mining.

