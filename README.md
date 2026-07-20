# smart-device-management-system
## Project Overview
The Smart Device Management System is a Python-based console application that demonstrates the principles of Object-Oriented Programming (OOP). It allows users to manage different smart home devices such as smart lights, security cameras, and temperature sensors through an interactive menu.

The project showcases important OOP concepts including:
- Classes and Objects
- Inheritance
- Encapsulation
- Method Overriding
- Polymorphism

The application defines a base `SmartDevice` class and extends it into specialized device classes with unique functionalities. :contentReference[oaicite:0]{index=0}

---

## Features

- Display information for all smart devices
- Turn all devices ON
- Turn all devices OFF
- Read temperature from the temperature sensor
- Increase or decrease smart light brightness
- Start and stop security camera recording
- Interactive menu-driven interface

---

## Devices Included

### Smart Light
- Power ON/OFF
- Increase brightness
- Decrease brightness
- Display device information

### Security Camera
- Power ON/OFF
- Start recording
- Stop recording
- Display recording status

### Temperature Sensor
- Power ON/OFF
- Read temperature
- Display current temperature

---

## Technologies Used

- Python 3
- Object-Oriented Programming (OOP)

---

## Program Structure

```
SmartDevice
│
├── SmartLight
├── SecurityCamera
└── TemperatureSensor
```

The `SmartDevice` class serves as the parent class, while the other three classes inherit its common properties and methods and implement additional device-specific functionality. :contentReference[oaicite:1]{index=1}

---

## How to Run

1. Install Python 3.
2. Download the project files.
3. Open a terminal or command prompt.
4. Navigate to the project folder.
5. Run the program:

```bash
python "smart device.py"
```

---

## Menu Options

```
1. Display Information
2. Turn Devices ON
3. Turn Devices OFF
4. Read Temperature
5. Adjust Brightness
6. Recording
7. Exit
```

The application continues running until the user selects **Exit**. :contentReference[oaicite:2]{index=2}

---

## OOP Concepts Demonstrated

### Encapsulation
Private attributes such as `__device_id` and `__power` are protected using getters and setters.

### Inheritance
The `SmartLight`, `SecurityCamera`, and `TemperatureSensor` classes inherit from the `SmartDevice` class.

### Polymorphism
Each child class overrides the `display_info()` method to include device-specific information.

### Abstraction
The parent class provides common functionality while each child class implements specialized behavior.

---

## Future Improvements

- Save device information to a file or database
- User authentication
- Add more smart devices (Smart Fan, Smart Door Lock, Smart Thermostat)
- Graphical User Interface (GUI)
- Real-time sensor simulation

---

## Author
Abdul-Mumin Benedict

---

## License

This project is created for educational purposes and may be modified or distributed for learning and academic use.
