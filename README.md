# ESP8266-Autoconnect
Modified Autoconnect Code for ESP8266

ESP8266 connects to WiFi when the last saved SSID and Password match those of the current network.
If not, ESP8266 goes into access point mode. If the user connects to the access point a webpage opens up and allows the user to configure the WiFi SSID and Password

Modification : Sometimes, the ESP does not connect to WiFi after changing the said values. So WiFimanager.cpp has been modified in such a way that ESP resets once the changes have been made.
