# Industrial-safety-alert
### **Objective:**
 In the industry, buzzers are used in warning systems and by using Pulse-Width-Modulation (PWM) different tones can also be generated on the buzzer.

**Hardware required:**

- 1 x Bolt IoT Module
- 1 x Micro USB Cable
- 1 x Buzzer
- 2 x Female to male wires

Procedure:

STEP-1 : Connect the circuit to the cloud.

STEP-2 : Configure the device. Write a js code for the buzzer.

```
<!DOCTYPE html>
<html>
    <head>
        <title>Bolt IoT Platform</title>
        <script type="text/javascript" src="https://cloud.boltiot.com/static/js/boltCommands.js"></script>
        <script>
        setKey('{{API_KEY}}','{{DEVICE_ID}}');
        </script>
    </head>
    <body>
        <center>
        <button onclick="digitalWrite(0, 'HIGH');">ON</button>
        <button onclick="digitalWrite(0, 'LOW');">OFF</button>
        </center>
    </body>
</html>

```
