# task2
Objective:
The goal of the code is to control 4 DC motors using Arduino and an L293D Motor Driver. The motors will perform the following movements:

Move forward for 30 seconds.
Move backward for 1 minute.
Alternate between moving right and left for 1 minute.
Code Explanation:
Pin Definitions:

Each motor is connected to different pins on the Arduino board via the L293D driver.
enA, enB, enC, enD: These pins control the speed (PWM) for each motor.
in1 to in8: These pins control the direction of the motors.
The setup() function:

All pins are set to OUTPUT mode.
Initially, the motors are stopped by calling the stopMotors() function.
The loop() function:

Move Forward (moveForward): The motors are made to move forward for 30 seconds using delay(30000).
Move Backward (moveBackward): Afterward, the motors move backward for 1 minute using delay(60000).
Alternate Right and Left (alternateRightLeft): Then, the motors alternate between moving right and left for 1 minute using millis().
Movement Functions:

moveForward(): Makes the motors move forward.
moveBackward(): Makes the motors move backward.
turnRight(): Makes the motors turn right.
turnLeft(): Makes the motors turn left.
stopMotors(): Stops the motors.
Alternating Between Right and Left:

In the alternateRightLeft() function, the motors alternate between turning right and left for 1 minute. Each direction lasts for 1 second, followed by a 0.5-second pause
![Image](https://github.com/user-attachments/assets/07e5ebe5-6634-4eae-9b20-4b8a2d4e6d30)
