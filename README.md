# ESP_MQTT
MQTT Daten von einem ESP8266 (Micropython) an einen Ubuntu Server (Broker und MySQL) übergeben und auf einer Webseite (Apache, Mysql and PHP) ausgeben.

Wir benötigen: 
* Einen ESP8266 oder ESP32
* Einen oder mehrere Sensoren  
  * Ich benutze einen DHT22 für Luftfeuchtigkeit und Temperatur, 
  * einen BMP180 für den Luftdruck (Temperatur ist zu ungenau) und 
  * einen vCapacitive Soil Moisture Sensor für die Bodenfeuchtigkeit.
* Einen Webserver mit
  * Apache (Webserver)
  * Mysql (Datenbank)
  * PHP (Webseite erstellen)
  * Python (Daten von Mosqitto in die Datenbank)
  * Mosquitto (MQTT Broker)

Im ersten Schritt verwende ich Micropython um die Connectivität zum Server und das auslesen der Sensoren zu Testen.
