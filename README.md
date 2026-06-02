# Countdown Timer

A simple command-line Countdown Timer written in Python. The user enters a duration in seconds, and the program counts down to zero, displaying the remaining time in `HH:MM:SS` format.

## Features

* Accepts countdown duration in seconds.
* Displays time in hours, minutes, and seconds.
* Updates every second in real-time.
* Notifies the user when the countdown is complete.
* Demonstrates the use of loops, time calculations, and Python's `time` module.

## Requirements

* Python 3.x

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/rohitdahiya04/countdown-timer.git
```

2. Navigate to the project directory:

```bash
cd countdown-timer
```

3. Run the program:

```bash
python main.py
```

## How to Use

1. Enter the countdown duration in seconds.
2. The timer will begin counting down immediately.
3. The remaining time will be displayed in `HH:MM:SS` format.
4. Once the timer reaches zero, the program displays:

```text
TIME'S UP!
```

## Example

```text
Enter the time in seconds: 10

00:00:10
00:00:09
00:00:08
00:00:07
00:00:06
00:00:05
00:00:04
00:00:03
00:00:02
00:00:01

TIME'S UP!
```

## Project Structure

```text
countdown-timer/
│
├── main.py
└── README.md
```

## Skills Demonstrated

* Python Loops (`for`)
* User Input Handling
* Arithmetic Operations
* Time Management with `time.sleep()`
* String Formatting (f-strings)
* Countdown Logic

## Future Improvements

* Add sound notifications when the timer ends.
* Allow users to enter hours, minutes, and seconds separately.
* Create a graphical user interface (GUI).
* Add pause and resume functionality.
* Display the countdown on a single updating line.

## Author

Rohit Dahiya

* GitHub: https://github.com/rohitdahiya04

## License

This project is open source and available under the MIT License.
