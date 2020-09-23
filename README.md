# ARM-PWM-MotorControl

In this project with the help of STM32 Smart V2.0 and L298N driver and a rotor,a motor controller setup is built by which we can control the speed of the spinning.We take advantage of PWM and duty cycle concept here so that we can increase or decrease the average voltage applied to motor's terminals.
We control the speed via two switches,one for lowering the speed and one for raising it.
Note:We can't supply the demanded current for the rotor via our microcontroller(if you do the micro will most definitly burn out) so we use the L298N third-party driver.Although if you wish not to use the driver,you can try it out with an LED or some other thing that will not exceed the 20 mA limit for the current. 
This project was built by CubeMX and Keil.
Also if you're interested in having the whole project,contact me.
