# ControlTheSpeedOfDcMotor
STM32F429 DISCO board - control the speed of a dc motor using a button - C code

I write a program to control the speed of a dc motor using a button.  For controlling the speed of the motor, the motor should be driven with PWM waveform and PWM duty cycle should be changed with the button. The PWM duty cycle ranges between 10% and 80%. The button operates in two modes as down and up. In the up mode, each time you press the button the PWM duty cycle is increased by 10%. In the down mode, each time you press the button the PWM duty cycle is decreased by 10%. To swich between modes, the button held down for more than 2 seconds.

I write the code for STM32F429 DISCO board.
