# Clock and Calendar

A simple digital clock and monthly calendar app built with Unity (2021.3 LTS) and TextMesh Pro.

![Capture](https://user-images.githubusercontent.com/54839430/205130672-1221a728-a6c7-46ce-98a6-f6bfffed71fb.PNG)

## Features

- **Digital clock**: shows the current time in 24-hour `HH:MM:SS` format, updated live.
- **Monthly calendar**: lays out the days of the current month on a weekday grid, with today highlighted in green.
- **Month and year header**: shows the current month and year (e.g. *November 2026*).
- Reads the device's local system date and time, so no setup is needed.

## Getting Started

1. Clone the repository.
2. Open the project in **Unity 2021.3.45f2** (or a compatible 2021.3 LTS version).
3. Open `Assets/Scenes/Digital.unity` and press **Play**.

A prebuilt Android build is available at `Build/ClockAndCalendar.apk`.

## Project Structure

| Path | Description |
| --- | --- |
| `Assets/Scenes/Digital.unity` | Main scene |
| `Assets/Scripts/GameManager.cs` | Updates the clock and fills in the calendar grid |
| `Assets/Prefabs/DateBox.prefab` | A single day cell in the calendar grid |
| `Assets/Sprites/` | Background artwork |
