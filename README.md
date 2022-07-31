# ARM-PWM-MotorControl

## In this project with the help of STM32 Smart V2.0, L298N driver and a rotor, a motor controller setup is built by which we can control its RPM.

In this project, we'll take advantage of PWM and duty cycle concept in order to increase or decrease the average voltage applied to the motor's terminals.
We control the speed via two switches,one for lowering the speed and one for raising it.

**Note:** It's not recommended to supply the demanded current for out rotor directly via our microcontroller (if you do the micro will most definitly burn out), so we use the L298N third-party driver. 

However, if you don't wish to use the driver, you can try it out with an LED or some other electronic device that does not exceed the 20 mA limit for the current. 

### This project was built by CubeMX and Keil.
### Also if you're interested in having the whole project, shoot me a message.
