### Demo Crouton device for ESP8266

This demo has a togglable led on pin 14 and a dimmable led on pin 12. It is intended to be used with [Crouton](http://crouton.mybluemix.net/). The MQTT Broker that it connects to in this demo is [test.mosquitto.org](test.mosquitto.org)

Using [luatool.py](https://github.com/4refr0nt/luatool) to upload code:

```bash
./luatool.py --port /dev/cu.usbserial --src main.lua --dest main.lua
```

Be sure to upload both init.lua and main.lua

Learn more about [Crouton](http://crouton.mybluemix.net/), *a dashboard that lets you visualize and control your IOT devices with minimal setup*

-------

Code provide under the MIT License
