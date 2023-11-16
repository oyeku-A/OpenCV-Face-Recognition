# OpenCV Face Recognition Project

## Overview

Welcome to the OpenCV Face Recognition project! This project aims to provide a simple yet powerful face recognition system using the OpenCV library.

## Table of Contents

- [OpenCV Face Recognition Project](#opencv-face-recognition-project)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Features](#features)
  - [Contributing](#contributing)

## Installation

To get started with the OpenCV Face Recognition project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/oyeku-A/OpenCV-Face-Recognition.git
   ```
2. Navigate to the cloned repository directory:

   ```bash
   cd OpenCV-Face-Recognition
   ```

3. Create a virtual environment:    
    ```bash
    python -m venv venv
    ```
4. Activate the Virtual Environment (used to isolate the project):
     ```bash
    source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
    ```
5. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

Once the installation is complete, you can use the face recognition system by running the main script:

```bash
python app.py
```
After running successfully, you can access the project locally. Open a web browser and navigate to http://127.0.0.1:5000/

_**Shutdown the Application**_ :

To stop the application, you can typically press Ctrl+C in the terminal where the application is running.

_**Deactivate the Virtual Environment**_ :
```bash
deactivate
```


This script will utilize OpenCV to capture video from your webcam and perform face recognition in real-time. You can customize the script according to your requirements.

## Features

- **Real-time Face Recognition**: The project provides a real-time face recognition system using OpenCV, making it suitable for various applications.
- **Easy Integration**: The system is designed to be easily integrated into existing projects or used as a standalone application.
- **Customizable**: You can customize the face recognition parameters and integrate additional features based on your project's needs.

## Contributing

If you want to contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them.
4. Push your changes to your fork.
5. Create a pull request to merge your changes into the main repository.