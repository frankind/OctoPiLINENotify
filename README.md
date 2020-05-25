# OctoPi do LINENotify with Nodered
- If you have raspberry PI, so you can use octopi/print to use Nodered to send the printing progress with you webcam snapshot.
- Normally I use Android device with IPWebcam

# Prerequisite
- Port forwarding to grab your image url (from IP Webcam) to Nodered
- Octopi or Octoprint with webhook plugin
- Install Nodered (https://nodered.org/docs/getting-started/raspberrypi)

# Webhook config
- URL http://<your nodered/myoctopi/lineNotify

# Nodered
- Just copy content in doYourNotify.json and import into nodered
- Configure as you need
