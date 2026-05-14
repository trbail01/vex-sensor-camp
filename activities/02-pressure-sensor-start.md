# Mission 2: Pressure Sensor Start

- Time estimate: 15-20 minutes

## Goal

Use the back pressure sensor to start the robot after a press.

## Sensor Used

- Pressure sensor on the back

## Setup

- Put the robot on a clear surface
- Make sure the back sensor can be pressed by hand
- Leave room in front of the robot for a short drive forward

## Student Task

Program the robot so it waits until the pressure sensor is pressed, then drives forward or performs another simple action.

## Basic Pseudocode

```text
wait until pressure sensor is pressed
drive forward
stop
```

## Middle School Version

- Treat the sensor like a start button.
- Use a simple if/then or wait-until structure.
- Celebrate the first successful press and movement.

## High School Version

- Store the press state in a variable such as startPressed.
- Use a loop to keep checking the sensor value.
- If the sensor is pressed, set the variable and start the action.

## Extensions

- Use the pressure sensor as a reset or stop button
- Add a second action after the first drive, such as turning or opening the claw
- Try a long press versus a short press if your software supports it

## Troubleshooting

- Check that the sensor is plugged into the correct port
- Confirm that the code is reading the right sensor, not a different button or input
- Make sure the robot is not already starting from another program branch
- If it never triggers, test the live sensor reading first

## Reflection Questions

- What happened when the sensor was pressed?
- Was the robot reaction immediate or delayed?
- What made the sensor feel like a button instead of a measuring tool?
- How could this idea be used in a real system?
