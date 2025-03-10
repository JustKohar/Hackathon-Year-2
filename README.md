# Insulin Tracker Application

# EXE INSTALLATION

https://www.dropbox.com/scl/fi/r0evd67fdoyq8dszdy5h3/InsulinHelperInstaller.zip?rlkey=66rpha4floyb0831m4hmb1j2c&st=lwftgh2q&dl=0

# Website for Diabeasy

https://diabeasy.org/

A Python-based application for tracking insulin usage, calculating doses, and maintaining a secure history of treatments.

## Features
- **User Authentication**: Secure login and registration system
- **Insulin Calculation**: Automatic dose calculation based on blood sugar levels
- **History Tracking**: Maintains a secure, encrypted history of all calculations
- **Profile Management**: Customizable insulin profiles for different times of day
- **Data Export**: Generate PDF reports of treatment history
- **Responsive UI**: Clean, modern interface with intuitive controls
- **EXE**: There is an exe able to download on the computer for easy use
- **Data Tracking Graph**: All Data is Logged on a Graph
- **History Deletion and Editing**: Ability to Clear History for Privacy and Remove Single Entries for Mistaken Entries

## Requirements

### Python Packages
Install the required Python packages using pip:
```bash
pip install cryptography pdfkit matlib matlab matplotlib

### wkhtmltopdf Installs: : Required for PDF generation
Windows: Download from wkhtmltopdf.org
macOS: brew install wkhtmltopdf
Linux: sudo apt-get install wkhtmltopdf


### HOW TO CLONE
git clone https://github.com/JustKohar/Hackathon-Year-2.git
cd Hackathon-Year-2

### TO RUN
python main.py

### FILE STRUCTURE
insulin-tracker/
├── main.py              # Application entry point
├── auth.py              # Authentication handling
├── data_manager.py      # Secure data storage
├── gui.py               # Main application interface
├── profile_manager.py   # Insulin profile management
├── history.py           # History tracking and display
├── login_image.png      # Login screen image
└── README.md            # This file
----------------------------------------------------------
Usage
Login Screen
Username: Enter your registered username

Password: Enter your password

Register: Create a new account if you don't have one

Main Application
Profile Setup: Configure your insulin profile

Calculator: Enter current blood sugar and time for dose calculation

History: View and manage treatment history

Logout: Securely end your session

Data Security
All user data is encrypted using AES-256

Passwords are hashed using SHA-256

Data files are stored in system-specific secure locations

Reporting Issues
Please report any issues via GitHub Issues with:

Detailed description of the problem

Steps to reproduce
