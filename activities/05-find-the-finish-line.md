# Mission 5: Find the Finish Line

- Time estimate: 15-20 minutes

## Goal

Use the optical sensor on the bottom to detect a finish line or target zone.

## Sensor Used

- Optical sensor on the bottom

## Setup

- Put black tape, colored paper, or a marked target zone on the floor
- Make sure the robot can drive over the line or into the zone
- Test the floor surface before the camp so the sensor behaves consistently

## Student Task

Drive the robot until the optical sensor detects the finish line, then stop.

## Basic Pseudocode

```text
drive forward
if finish line is detected
  stop
```

## Middle School Version

- Treat the line as a clear yes/no signal
- Ask students to watch what happens when the robot crosses the tape
- Keep the code focused on one decision

## High School Version Using Optical Sensor Values and Thresholds

- Read the sensor value instead of only using a simple yes/no check
- Store the threshold in a variable such as lineThreshold
- Compare the live reading to the threshold and stop when the value crosses it

## Troubleshooting

- Make sure the optical sensor points at the floor
- Try a different tape color or paper if the sensor reading is unclear
- Check lighting conditions if the reading changes too much
- Re-test the threshold on the actual floor, not just on paper

## Discussion Questions

- Why might a robot need to notice the floor?
- What changed when you adjusted the threshold?
- How is this like a smart door, a line-following robot, or a security system?
