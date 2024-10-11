
# UAV Project: CRYSTALS-Kyber-and-IDS

## Description

This project implements a secure communication system using the CRYSTALS-Kyber encryption algorithm. It includes server and client applications designed for file transfer and secure messaging.

## Getting Started

Follow these steps to set up and run the project on your local machine.

### Prerequisites

Make sure you have Python installed on your system (Python 3.7 or later recommended).

### Step 1: Clone the Repository

Clone the project repository from GitHub:

```bash
git clone https://github.com/Jovit-Mathew236/UAV_project/
cd UAV_project
```
### Step 2: Set Up a Virtual Environment

Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate  # For Windows
# source venv/bin/activate  # For macOS/Linux
```

### Step 3: Install Required Packages

Install the necessary Python packages:

```bash
pip install tqdm psutil pycryptodome cryptography
```

### Step 5: Set the Python Path

Set the Python path to ensure the modules can be imported correctly. Adjust the path to match your project directory:

```bash
set PYTHONPATH=%cd%  # For Windows
# export PYTHONPATH=$(pwd)  # For macOS/Linux
```

### Step 6: Run the Server

Open a new terminal, navigate to the project folder, activate the virtual environment, and run the server:

```bash
python server/server.py
```

### Step 7: Run the Client

Open another terminal window, activate the virtual environment, and run the client:

```bash
venv\Scripts\activate
set PYTHONPATH=%cd%  # For Windows
python clients/client_1.py
```

### Step 8: Sending Files

Follow the prompts in the client terminal to choose between ECC and CRYSTALS-Kyber. You can send files by specifying the file path, for example:

```bash
file:client_files/your_file.jpg
```

## Conclusion

You have successfully set up and run the CRYSTALS-Kyber-and-IDS project! Feel free to modify the code and explore the encryption features.
