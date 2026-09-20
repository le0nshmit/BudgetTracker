# ![Budget Tracker Logo](./images/budget-tracker-logo.png)
***

This project is focused on learning C integration with Python, 
once I have basic functionality I will look to optimise code and improve.

## Getting Started

***

Follow these instructions to correctly setup the project and run it on your
local machine for development and testing purposes! 

### Prerequisites

- Python3
- GCC
- pip


#### Python

Install Python3:

sudo apt update && sudo apt install python3 -y

Create Environment in project root:

python3 -m venv .venv

Install Python Dependencies in project root:

pip install -r requirements.txt

Dependencies Included:

- Flask
- Matplotlib


#### C

The C component requires GCC to compile.

On Debian-based Linux distros, install GCC:

sudo apt update && sudo apt install gcc -y

#### Compiling C

gcc <source-file> -o <program-name>

For Example:

gcc hello.c -o hello

Run Program:

./hello 



