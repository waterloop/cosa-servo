# Cosa Servo

This is a wio package for Cosa that allows access to Servo and provides functionality to control them

## Usage

Define a servo using `Servo servo(0, Board::D9)` and start it using `Servo::begin()`

Control the servo using:
```cpp
servo.angle(10);
```

## Install
```bash
wio install cosa-servo
```
