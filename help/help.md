# Pigetcam
```
IP ADDRESS : https://camera.local or http://192.168.0.1:8080
IMAGE URL  : ?camera=snapshot	 	
```

# Mjpeg-streamer
```
IP ADDRESS : http://camera.local:8080 or http://192.168.0.1:8080
IMAGE URL  : ?action=snapshot
```

# Pigetcam Installation (camera module)
````
/pi/install camera
/do/camera/enableCameraModule
reboot
/pi/install/mjpeg-streamer
/do/mjpeg-streamer/streamAsService
/pi/install/pigetcam
````

# Pigetcam Installation (webcam)
````
/pi/install camera
/do/camera/enableCameraModule
reboot
/pi/install/mjpeg-streamer
/do/mjpeg-streamer/streamAsService
/pi/install/pigetcam
````

# Mjpeg-streamer w/ kana
````
/pi/install camera
/pi/install/mjpeg-streamer
/do/mjpeg-streamer/streamAsService
