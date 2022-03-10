# ESP_MQTT
MQTT Daten von einem ESP8266 (Micropython) an einen Ubuntu Server (Broker und MySQL) übergeben und auf einer Webseite (Apache, Mysql and PHP) ausgeben.

Wir benötigen: 
. Einen ESP8266 oder ESP32
. Einen oder mehrere Sensoren  
.. Ich benutze einen DHT22 für Luftfeuchtigkeit und Temperatur, 
.. einen BMP180 für den Luftdruck (Temperatur ist zu ungenau) und 
.. einen vCapacitive Soil Moisture Sensor für die Bodenfeuchtigkeit.

Im ersten Schritt verwende ich Micropython um die Connectivität zum Server und das auslesen der Sensoren zu Testen.
