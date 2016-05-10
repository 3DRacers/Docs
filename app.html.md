---
title: 3DRacers - App Guide


toc_footers:
  - <a href='http://store.3dracers.com'>Buy 3DRacers</a>
  - <a href='https://github.com/3DRacers/3D-Models'>Download 3D models STL</a>
  - <a href='/docs/app.html'>Download iOS/Android App</a>
  - <a href='/editor'>Online Editor</a>

search: true
---

# App guide

With 3DRacers you can drive your 3D Printed car with the free Smartphone App: [iOS](https://itunes.apple.com/en/app/3dracers/id1054404136) or [Android](https://play.google.com/store/apps/details?id=com.Lib3DRacers.Lib3DRacers) app.

### Other sections
[Documentation](/docs) - [Online Editor](http://www.3dracers.com/editor) - [Coding Guide](/docs/code.html)

![3DRacers Game](/docimages/app-main.jpg?raw=true "3DRacers Smarthone App")
 
## Connect to your Car

Simply starting a new game will prompt the connect dialog, or you can do it manually by touching the Connect button or the car name on the top bar.

To connect to your car, turn it on, it will pulse cian. 

The name of your car will shows in the Connect dialog, you can then touch it to connect. Wait some seconds untily the Blue light of the 3DRacers stop.

Be sure to turn on the Bluetooth radio on your device. If you have trouble connecting, switch off the 3DRacers car and turn on back again.

## Car Setup

![3DRacers Game](/docimages/app-car-setup.jpg?raw=true "3DRacers Smarthone App Car Setup")

 - **Steering Center** If your car drift left or right, you can compensate it with the Steering Center setting.

 - **Max Radius** Set so that the wheels will not touch the car even at the maximum steering radius, or the Servo will emit a noise when going to the max. This could damage the Servo.

 - **Rename** In this dialog you can also rename your car. After that you'll need to reconnect to it.
 
 - **Invert** You can invert the direction of the steering or throttle. Usefull if you are creating custom vehicles.

## Driving

![3DRacers Game](/docimages/app-driving.jpg?raw=true "3DRacers Smarthone App Driving")

You can control your car with Analog or Digital controls. Customizable in the Controls settings dialog.

If you have trouble driving your 3DRacers, try using the Easy difficulty setting. Also remember to set the correct Track Size: if the car goes too fast it will be impossible to stay on track with tight bends.

To go reverse, hold the brake pedal.

 - **Difficulty** Quick settings for max speed and control style. Set to **Custom** to modify the values.
 
 - **Track Size** Set it accordingly to your track size: if < 3mt, < 6mt, < 10mt. 
 
 - **Max Speed** Limit the car speed. Usefull when driving in a constrained space
 
### Digital Steering

 - **Steering Angle** Reduce the angle of the car when the left or right button is pressed
 - **Steering Stabilization** When enabled will reduce the steering angle when the speed is high, to avoid spinning.
 
### Ananlog Steering

 - **Dead Zone** The central zone of the wheel where the car goes straight
 - **Movement Smoothing** Smooth the steering
 - **Steering Stabilization** When enabled will reduce the steering angle when the speed is high, to avoid spinning.
 
### Digital Throttle

 - **Limit Acceleration** When the throttle pedal is pressed, the car will gain that percentual of the Max Speed each second.

### Analog Throttle

 - **Dead Zone** The resting position of the controls
 - **Smoothing** Smooth the speed changes

## Speed Control

Since the DC motor on board of a 3DRacers has a really high torque compared to the light weight of the car, it is important to lower the Max Speed to a confortable level, otherwise it will be really difficult to follow a path and avoid spinning.

Also, with the **Analog Throttle** controls, the speed of the car will be binded to the amount of power given via the controls: lowering the bar will slow down the car, even on slopes. This is the `Throttle=Speed` mode

This direct correlation between speed and throttle will make it easier to drive, but can be changed to a more realistic value (`Throttle=Acceleration`) with the `MOTOR_MODE_PH_EN` constant in Arduino. See the [Coding Guide](/docs/code.html)

## Comments

<div id='discourse-comments'></div>

<script type="text/javascript">
  DiscourseEmbed = { discourseUrl: 'http://forum.3dracers.com/',
					 discourseEmbedUrl: 'http://www.3dracers.com/docs/app.html' };

  (function() {
	var d = document.createElement('script'); d.type = 'text/javascript'; d.async = true;
	d.src = DiscourseEmbed.discourseUrl + 'javascripts/embed.js';
	(document.getElementsByTagName('head')[0] || document.getElementsByTagName('body')[0]).appendChild(d);
  })();
</script>
