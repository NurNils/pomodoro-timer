<!-- Logo -->
![Example Image](./example.jpg?raw=true)

# Pomodoro Timer 

The Pomodoro Technique is a time management method developed by Francesco Cirillo in the late 1980s. It uses a kitchen timer to break work into intervals, typically 25 minutes in length, separated by short breaks. Each interval is known as a pomodoro, from the Italian word for tomato, after the tomato-shaped kitchen timer Cirillo used as a university student.

<!-- Social Media -->
[![GitHub Repo stars](https://img.shields.io/github/stars/NurNils/pomodoro-timer?style=social)](https://github.com/NurNils/pomodoro-timer)
[![GitHub followers](https://img.shields.io/github/followers/NurNils?style=social)](https://github.com/NurNils)


## About
This project was developed by Nils-Christopher Wiesenauer (NurNils) to show working and break phases on stream. The main purpose of this project is the development of a fully customizable pomodoro timer.

🍅 Fully customizable pomodoro timer

📝 Licensed under MIT: Do almost anything you want with this project files

## Table of Contents

- [Installation and Usage](#Installation-and-Usage)
  - [Files](#Files)
  - [Import to your stream](#Import-to-your-stream)

## Installation and Usage

### Files

Download this project and save it in a desired folder. Now you can edit your pomodoro timer by replacing the `sound.mp3` or editing the `pomodoro.html` file. Just update the following variables:

```javascript
// Time for work (in seconds, typically 25 minutes)
var timeWork = 25 * 60;
  
// Time for pause (in seconds, typically 5–10 minutes)
var timePause = 5 * 60;

// Time for big pause (in seconds, typically 20 to 30 minutes)
var timePauseBig = 20 * 60;

// Amount of working phases till big pause
var timeWorkAmount = 3;
```

### Import to your stream

After downloading and editing all files, open your streaming software (e.q. [OBS Studio](https://github.com/obsproject/obs-studio)). Go to sources > Add source > Browser > Local file > Click on "Browse" > Choose file (`pomodoro.html`) and active "Shutdown source when not visible. That's it! :)

