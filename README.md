# Create your LINE Notify
- https://digitalarea.co/line-notify-beginner/
- Copy your access token, then paste it in code after you have imported the flow in nodered

# OctoPi do LINENotify with Nodered
- If you have raspberry PI, so you can use octopi/print to use Nodered to send the printing progress with you webcam snapshot.
- Normally I use Android device with IP Webcam app (Free with ads)

# Install first
- Install Nodered (https://nodered.org/docs/getting-started/raspberrypi) in your raspberry pi
- Install Octopi or Octoprint with webhook plugin

# Prerequisite
## Option 1 using your image url within PI
- Need port forwarding to grab your image url (from IP Webcam) to Nodered
- Octopi or Octoprint with webhook plugin

## Option 2 using your local image within PI
- No need port forwarding
- Anyway we need to capture new image for each progress, so I still call internal webcam service and store it into a file.(You can change it in a proper way)

# Webhook config
- URL http://<your nodered>/myoctopi/lineNotify

# Nodered
## Use Option 1
- Use doYourNotify.json and import into nodered


## Use Option 2
- Use doYourNotifyLocalFile.json and import into nodered
