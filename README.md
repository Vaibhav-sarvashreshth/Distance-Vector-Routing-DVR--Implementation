# Distance Vector Routing Protocol

This repository contains an implementation of the Distance Vector Routing Protocol in Python. The protocol is implemented using multithreading, where each thread represents a router instance. The routers communicate with each other through a shared queue.

## Assignment Description

The assignment requires implementing the Distance Vector Routing Protocol in Python, following a decentralized approach. The program should parse input to understand the topology of the network, calculate the routing tables using the Bellman Ford equation, and display the routing tables after each iteration. The routers should forward their routing tables to adjacent routers through a shared queue, update their tables, and repeat the process until convergence.

## Repository Contents

The repository contains the following files:

- `DVR.py`: This file implements the Distance Vector Routing protocol. It takes `inp.txt` as an input parameter, which contains the topology information in the prescribed format.
- `inp.txt`: This file represents the input topology of the network, including the number of routers, the fixed names (interfaces) of the routers, and the costs of the links connecting the routers.
- `inp.txt`: This file represents the input topology of the network, including the number of routers, the fixed names (interfaces) of the routers, and the costs of the links connecting the routers.

- `input for testing.txt`: This file provides additional input examples for testing the Distance Vector Routing Protocol.
- `BT20CSE083_Vaibhav_Mokale_Assignment_Presentation.pptx`: This PowerPoint presentation explains the Distance Vector Routing Protocol, the code flow, and includes screenshots of the `inp.txt` file and the program's output.
- `BT20CSE083_Vaibhav_Mokale_A3.pdf`: This PDF document explains the code flow of the implementation and includes screenshots of the `inp.txt` file and the program's output.


- `readme.txt`: This file provides instructions for running the code and additional information about the assignment.

## Instructions for Running the Code

To run the code, follow these steps:

1. Clone the repository:

    ```sh
    git clone https://github.com/Vaibhav-sarvashreshth/Distance-Vector-Routing-DVR--Implementation.git
    ```



2. Navigate to the repository directory:

    ```sh
    cd Distance-Vector-Routing-DVR--Implementation
    ```




3. Ensure you have Python installed on your system.

4. Run the `DVR.py` script, providing `inp.txt` as the input parameter:
    ```sh
    python DVR.py
    ```


5. The program will display the routing tables after each iteration, showing the updated entries marked with an asterisk (*).

## Demonstration Video

For a detailed explanation of the code and demonstrations of various test cases, please refer to the accompanying video file.


