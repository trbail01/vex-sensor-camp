# Home Assistant Sensor Demo

## Demo Purpose

Show that the same input, logic, output pattern used in VEX robot programming also shows up in smart homes and automation systems.

## Materials

- Raspberry Pi
- Home Assistant
- Aqara Zigbee motion sensor
- Aqara door/window sensor
- Smart bulb or smart switch

## Setup Overview

- Connect the Raspberry Pi to Home Assistant
- Add the Aqara devices to Home Assistant
- Pair the smart bulb or smart switch
- Keep the dashboard visible so students can watch the automation trigger

## Demo 1: Motion Sensor Turns on a Light

1. Show the motion sensor as the input.
2. Explain the Home Assistant rule as the logic.
3. Turn on the smart bulb as the output.
4. Trigger the sensor and watch the light respond.

## Demo 2: Door/Window Sensor Changes a Light or Switch

1. Show the door/window sensor on a door, box, or simple demo setup.
2. Explain that opening or closing changes the input.
3. Use Home Assistant to trigger the smart bulb or switch.
4. Compare the result to the robot missions.

## Connection Back to VEX Sensors

The robot and the smart home follow the same pattern:

- Input: a sensor notices something
- Logic: a rule decides what should happen
- Output: a device acts

## Input to Logic to Output Comparison

| System | Input | Logic | Output |
| --- | --- | --- | --- |
| VEX robot | Pressure, range, or optical sensor | Robot code | Drive, stop, or close the claw |
| Home Assistant | Motion or door/window sensor | Automation rule | Light turns on or switch changes |

## Discussion Questions

- What stayed the same between the robot and the smart home?
- What changed about the kind of input each system used?
- Which system felt easier to understand?
- Where else do you see this pattern in daily life?
