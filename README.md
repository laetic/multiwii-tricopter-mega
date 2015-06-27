# multiwii-tricopter-mega
copter club's sensor bristling tricopter

Here's the Multiwii code for our tricopter.
It's already configured but there are no major changes from Multiwii 2.4

Notes on the physical copter: 
- The arducopter shield is a bit weird in that the ESC (motor) plugins are power inputs and not outputs. Therefore if you want the servo to work you'll have to plug that into a different 5V plug on the board.
- Bluetooth goes into Serial 0, the same port as USB meaning you can't have both at once.
- GPS goes into Serial 2
