# Mission 4: Claw Grabber Challenge

- Time estimate: 20-25 minutes

## Goal

Use the range sensor and claw together to approach an object, stop, and grab it.

## Sensors/Mechanisms Used

- Range sensor
- Claw mechanism
- Drive motors

## Setup

- Place a small object in front of the robot
- Make sure the claw can open wide enough to grab the object
- Keep the target object in the sensor's path

## Student Task

Drive toward the object until it is close enough to grab, then stop and close the claw.

## Basic Pseudocode

```text
drive forward
if object is close enough
  stop
  close claw
```

## Middle School Version

- Keep the action simple: approach, stop, grab
- Let students adjust speed before changing the logic
- Focus on whether the claw actually gets the object

## High School Version

- Use a variable for the grab distance
- Add a loop that keeps checking the sensor while driving
- Let students tune the threshold and compare results

## Optional Scoring Table

| Attempt | Grabbed object? | Stayed on target? | Notes |
| --- | --- | --- | --- |
| 1 |  |  |  |
| 2 |  |  |  |
| 3 |  |  |  |

## Troubleshooting

- If the claw misses, slow down before changing the threshold
- Check that the object is centered in front of the robot
- Make sure the claw opens and closes correctly before the run
- If the sensor sees the object too late, check its angle and mount point

## Instructor Notes

- This mission usually gets students excited, so keep it moving.
- If one team is stuck, ask them to test the claw by itself before changing the whole program.
- Use this mission to reinforce that sensors help the robot decide when to act.
