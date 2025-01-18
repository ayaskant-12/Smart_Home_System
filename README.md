# SmartHomeSystem

A Java-based implementation of various design patterns to model a Smart Home System. This project demonstrates the usage of **Singleton**, **Command**, **Proxy**, **Bridge**, **Template Method**, **Composite**, and **Iterator** design patterns in a cohesive smart home environment.

---

## Features
1. **Singleton Pattern**  
   Manages the `SmartHomeHub` as a single global instance.

2. **Command Pattern**  
   Encapsulates device operations (e.g., turning devices ON/OFF) into command objects.

3. **Proxy Pattern**  
   Provides access control for devices based on user roles.

4. **Bridge Pattern**  
   Decouples abstraction (device controls) from implementation (control methods).

5. **Template Method Pattern**  
   Implements a morning routine with customizable steps.

6. **Composite Pattern**  
   Groups devices into hierarchical structures and performs operations on the entire group.

7. **Iterator Pattern**  
   Iterates over a collection of devices in a structured way.

---

## Code Structure
- **`SmartHomeHub`**  
  Manages a centralized list of devices in the smart home.

- **Command Pattern**  
  Classes: `TurnOnCommand`, `TurnOffCommand`, and `Device`.  
  Allows devices to be controlled via commands.

- **Proxy Pattern**  
  Classes: `DeviceProxy`, `RealDevice`.  
  Implements role-based access control for devices.

- **Bridge Pattern**  
  Classes: `DeviceControl`, `RemoteControl`, and `VoiceControl`.  
  Enables different control mechanisms for devices.

- **Template Method Pattern**  
  Classes: `Routine`, `MorningRoutine`.  
  Provides a template for executing a morning routine.

- **Composite Pattern**  
  Classes: `DeviceGroup`, `DeviceLeaf`.  
  Groups devices into composite structures and executes operations.

- **Iterator Pattern**  
  Class: `DeviceIterator`.  
  Provides a way to sequentially access devices.

---

## Usage
### Prerequisites
- Java JDK 8 or later installed.
- Basic understanding of Java and object-oriented programming concepts.

### How to Run
1. Clone the repository.
   ```bash
   git clone https://github.com/your-username/smart-home-system.git
   cd smart-home-system
2. Complile the code.
   ```bash
   javac SmartHomeSystem.java
3. Run the program
   ```bash
   java SmartHomeSystem

---
### Design Patterns Overview
#### 1. Singleton
Ensures only one instance of SmartHomeHub is created.

#### 2. Command
Encapsulates requests as objects for better flexibility in executing commands.

#### 3. Proxy
Adds a level of control to access devices based on user roles.

#### 4. Bridge
Separates abstraction from its implementation.

#### 5. Template Method
Defines a skeleton routine with specific steps implemented in subclasses.

#### 6. Composite
Handles both individual devices and groups uniformly.

#### 7. Iterator
Provides a standard way to iterate over a collection of devices.

---

## follow me

follow me on [github](https://github.com/ayaskant-12)

follow me on [instagram](https://www.instagram.com/ayaskant_dash_03/)
