# Resources

## Vocabulary

| Word | Meaning |
| --- | --- |
| Sensor | A device that collects information from the world |
| Input | The information a robot or system receives |
| Output | The action a robot or system performs |
| Logic | The decision-making part of code |
| Condition | A rule the program checks |
| Threshold | A value used to decide when to act |
| Loop | Code that repeats |
| Variable | A named place to store data or state |
| Automation | A system that responds automatically based on rules |
| Debugging | Finding and fixing problems in code |

## Pseudocode Examples

### Pressure Sensor Start

```text
wait until pressure sensor is pressed
drive forward
```

### Range Sensor Stop

```text
forever
  if distance is less than threshold
    stop driving
```

### Claw Grabber

```text
drive toward object
if object is close enough
  stop
  close claw
```

### Optical Sensor Finish Line

```text
forever
  if optical sensor detects dark line
    stop
```

### Emergency Stop

```text
forever
  if pressure sensor is pressed
    stop all motion
```

## Real-World Sensor Examples

| System | Sensor idea |
| --- | --- |
| Robot vacuum | Detects walls, edges, or obstacles |
| Automatic doors | Detects people approaching |
| Smartphones | Detects motion, light, or orientation |
| Cars | Use parking sensors and driver-assist systems |
| Smart homes | Use motion, door, and light sensors |
| Security systems | Detects doors, windows, or movement |
