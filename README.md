# Yagusmart-Tuya-ZigBee-Smart-Light-Switch
Home Assistant device handler for the Yagusmart Tuya ZigBee Smart Light Switch

https://www.aliexpress.com/i/4001217084809.html

1. Add this as a new device handler via the web interface https://account.smartthings.com
2. Use the smarthings app to search for a newrby thing. 
3. The device handler should automatically identify the switch and add it to your app.

Feartures
-------------------------------------------

- Automatic recognition f the device via the fingerprint ID
- Push, Held and double pressed acitons are recognised
- Multi gang switches/buttons recognised and child devices added automatically in the app

Known Issues as of 25/3/2021
-------------------------------------------

- The in app icon (Only tested on iOS) representing a switch with more than 1 gang are different.
- Not currently tested for a switch for 3 or 4 buttons (I didnt have these at the time of testing so let me know if anyone confirms this as working)
- Battery funciton not working (I'm not sure this device provides this status)
- Configuraiton of the time to recognise a "Held" button event doesn't work. (The device doesn't appear to report the time held.)
