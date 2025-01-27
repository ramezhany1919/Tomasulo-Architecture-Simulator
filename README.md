# Tomasulo Architecture Simulator 📊

## Project Description 📝
This simulator implements the Tomasulo algorithm to demonstrate dynamic scheduling to resolve conflicts in hardware. This Java and JavaFX project provides a graphical user interface (GUI) that visualizes instruction processing, reservations stations, register status, and execution in real-time.

## Features 🌟
- **Dynamic Instruction Scheduling**: Simulates the Tomasulo algorithm with real-time updates to reservation stations and registers.
- **Customizable Simulation Parameters**: Users can define the size of reservation stations and cache properties.
- **Graphical User Interface**: Allows for an interactive simulation with step-by-step execution through the GUI.

## Getting Started 🚀

### Prerequisites
- Java 11 or higher
- JavaFX SDK (Compatible with your Java version)

### Installation
1. Clone the repository or download the source code.
2. Navigate to the project directory.

### Configuration
Before running the simulator, ensure JavaFX is correctly configured on your IDE or command line setup.

## Usage 🛠️

### Running the Simulator
1. Compile and run the `Main.java` file using your IDE or the command line.
2. Load the instruction set and register file by placing your `.txt` files in the `src` directory.

### Input Files
- **Instructions.txt**: Contains a list of instructions to be processed.
    ```
    L.D F6, 0
    DADDI R1, R1, 260
    DADDI R2, R1, 353
    DSUBI R1, R2, 144
    DADDI R4, R1, 150
    L.D F2, 10
    ```

- **Registers.txt**: Initial state of registers.
    ```
    0
    20
    0
    0
    0
    0
    0
    0
    0
    0
    0
    0
    0
    0
    0
    0
    ```
    *Note: The first 32 elements correspond to the value of R(X) and the other 32 correspond to the value of F(X).*

### Using the GUI
- Configure the buffer sizes and latencies as prompted.
- Run the simulation to see the Tomasulo algorithm in action.

## Screenshots 📸
Welcome Screen
![Tomasulo Welcome](https://github.com/ramezhany1919/Tomasulo-Architecture-Simulator/blob/main/Tomasulo-Sim/Screenshots/Screenshot1.png "Welcome Screen")
Buffer Size Setup
![Tomasulo Simulation Buffer Size Setup](https://github.com/ramezhany1919/Tomasulo-Architecture-Simulator/blob/main/Tomasulo-Sim/Screenshots/screenshot2.png "Buffer Size Setup")
Latency Time Setup
![Tomasulo Simulation Latency Time Setup](https://github.com/ramezhany1919/Tomasulo-Architecture-Simulator/blob/main/Tomasulo-Sim/Screenshots/screenshot3.png "Latency Time Setup")
Cache Size Setup
![Tomasulo Simulation Cache Size Setup](https://github.com/ramezhany1919/Tomasulo-Architecture-Simulator/blob/main/Tomasulo-Sim/Screenshots/screenshot4.png "Cache Size Setup")
Simulation Running
![Tomasulo Simulation Running](https://github.com/ramezhany1919/Tomasulo-Architecture-Simulator/blob/main/Tomasulo-Sim/Screenshots/screenshot5.png "Simulation Running")


## Acknowledgments 🙏
- Inspired by the work on Tomasulo's algorithm for instruction-level parallelism.
