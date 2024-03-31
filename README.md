# Digital-Clock-Simulation

## Get Started
This repository contains a digital clock simulation designed to run on Arduino using a 16x2 LCD display, push buttons, and a piezo buzzer. The simulation not only displays the current time but also offers features such as setting time, alarm, timer, and a stopwatch. Additionally, it provides functionality to display temperature and date.

## Features

- **Time Display**: The clock accurately counts down displays the time once set.
- **Set Time**: Users can set the time using the provided push buttons.
- **Alarm**: Set alarms to go off at specific times.
- **Timer**: Set timers for countdown functionality.
- **Stopwatch**: Start, stop, and reset a stopwatch for timing events.
- **Temperature Display**: Shows the current temperature.
- **Date Display**: Displays the current date alongside time.

## Functionality

The core functions of the clock simulation are organized as follows:

- **`runningClock()`:** This function manages the main clock functionality, updating and displaying the current time, temperature, and date.
- **`setTime()`:** Enables users to set the time by adjusting hours, minutes, and seconds.
- **`setAlarm()`:** Allows users to set alarms for specific times.
- **`setTimer()`:** Provides functionality to set timers for countdown purposes.
- **`stopwatch()`:** Controls the stopwatch feature, allowing users to start, stop, and reset the stopwatch.

## User Interface

The clock simulation is controlled using push buttons, each assigned specific functions:

1. **Set Time:** Enables users to set the time and switches between different modes (time, alarm, timer, stopwatch).
2. **Set Alarm:** Used to set alarms.
3. **Stopwatch:** Starts the stopwatch.
4. **Set Timer:** Sets timers.
5. **Switch to Stopwatch:** Switches to stopwatch.

## Usage

Here are the step-by-step instructions to use the digital clock simulation:

### Setting Date
- The date can be changed directly in the code as needed.

### Testing Temperature
- Utilize the temperature sensor dial to test temperature functionality.

### Setting Time
1. Hold pushbutton 1 for 1 second to enter the set time option on the LCD.
2. Use pushbutton 2 to increment time and pushbutton 3 to decrement time.
3. Press pushbutton 4 to switch between setting hours and minutes.
4. Use pushbutton 5 to switch between AM and PM.
5. Once the desired time is set, press pushbutton 1 to confirm and set the time.

### Setting Alarm
1. Hold pushbutton 2 for 1 second to enter the set alarm option on the LCD.
2. Use pushbutton 2 to increment time and pushbutton 3 to decrement time.
3. Press pushbutton 4 to switch between setting hours, minutes, and seconds.
4. Use pushbutton 5 to switch between AM and PM.
5. Once the desired alarm time is set, press pushbutton 1 to confirm and set the alarm. The buzzer will indicate the alarm time.

### Setting Timer
1. Hold pushbutton 4 for 1 second to enter the set timer option on the LCD.
2. Use pushbutton 5 to start or stop the timer.
3. The end of the timer will be indicated by the LED.
4. Once the timer is set, press pushbutton 1 to return to the running clock.

### Stopwatch
1. Hold pushbutton 5 for 1 second to enter the stopwatch option on the LCD.
2. Press pushbutton 3 to start the stopwatch.
3. Press pushbutton 4 to stop the stopwatch.
4. Press pushbutton 5 to reset the stopwatch.
5. Once the stopwatch is stopped or reset, press pushbutton 1 to return to the running clock.

Follow these steps to navigate through the features and functionalities of the digital clock simulation using the provided push buttons and LCD display.


## Components

The components used are as follows:

| Component name | Description |
| --- | --- |
| 16*2 LCD Display | Used as clock display |
| LED (green) | Indicates the end of the timer |
| Pushbuttons | Used to control various features |
| Buzzer | Indicates the alarm going off |
| temperature Sensor | Used to simulate temperature changes |
| Resistors | For protection of the components |

***
Tinkercad is a browser-based platform that enables users to design, simulate, and prototype electronic circuits and 3D models..
Open and start simulation in Tinkercad: (https://www.tinkercad.com/things/f2lew1c554t-digital-clock-fin)
