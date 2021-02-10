# Home-Assistant

SETUP

1) Install Home Assistant (home-assistant.io) in Raspberry PI
2) Install Home Assistant Community Store | HACS in Home Assistant
3) Follow the 4$ Xiaomi Temperature Sensor for Home Assistant - Intermittent Technology (quindorian.org) tutorial
a. There is a need to install ESPHome — ESPHome
i.  Done using a HA plugin, no shell required
b. Flash the sensor using the firmware in caxaria/ATC_MiThermometer
i. Make sure to save the Mi Bind Key 
ii. Configure the esp32 if new 
iii. See Configure Wifi ESP32 YAML
iv. Compile
v. Deploy with https://github.com/caxaria/ESPHome-Flasher
1) Universal driver in CP210x USB to UART Bridge VCP Drivers - Silicon Labs (silabs.com)
c. Get logs in esphome and check Mac Address of sensor
d. Edit YAML to include the sensor and deploy Over-The-Air (OAT)
i. See Device YAML
