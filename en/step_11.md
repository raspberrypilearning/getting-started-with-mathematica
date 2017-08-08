## Camera

You can take pictures with the camera using the `DeviceRead` function. First, attach your camera as directed in the [camera setup guide](http://www.raspberrypi.org/help/camera-module-setup/).

To take a still picture with the camera, type the following command:

```
img = DeviceRead["RaspiCam"]
```

Then to save the image as a file, use `Export` and supply the save path and the variable containing the image:

```
Export["/home/pi/img.jpg", img]
```

