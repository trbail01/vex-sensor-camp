# Mission 3: Don't Hit the Wall

- Time estimate: 20 minutes

## Goal

Use the range sensor to stop the robot before it bumps into a wall or obstacle.

## Sensor Used

- Range sensor on the front near the claw

## Setup

- Place a wall, box, or object in front of the robot
- Make sure the front sensor points directly toward the target
- Leave enough space for several test runs

## Student Task

Drive toward the object and stop when the range sensor says the object is close enough.

## Basic Pseudocode

```text
drive forward
if object is too close
  stop
```

## Middle School Version

- Use a simple distance rule like "stop when it gets close"
- Let students test a few different stopping distances
- Keep the focus on seeing the robot respond before a collision

## High School Version with Threshold Variable

- Store the stopping distance in a variable such as stopDistance
- Compare the live sensor reading to that variable
- Try changing the threshold and comparing the results

## Testing Table for Different Stopping Distances

| Try | Threshold or stopping distance | Stopped before wall? | Notes |
| --- | --- | --- | --- |
| 1 | 100 mm |  |  |
| 2 | 150 mm |  |  |
| 3 | 200 mm |  |  |

## Troubleshooting

- Make sure the sensor is facing forward
- Check for glare, angle problems, or blocking objects
- Slow the robot down if it overshoots the stop point
- Confirm the reading is changing before debugging the code

## Real-World Connections

- Parking sensors in cars
- Robot vacuums avoiding walls and furniture
- Warehouse robots stopping before collisions
