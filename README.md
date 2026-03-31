# Automated Carwash

LabVIEW-based touchless car wash automation project built around a client-server style workflow. The system includes login validation, automation control logic, status handling, and simple file-backed records for demonstrating a software-driven car wash process.

## Features

- Touchless car wash process simulation
- LabVIEW client/server style control flow
- Login validation and session handling
- File-backed activity and purchase logging
- Modular VIs and control files for the workflow

## Repository Contents

- `Assignment.lvproj` - main LabVIEW project
- `Assignment.vi` / `Assignment server.vi` - primary workflow VIs
- `Login Validation (SubVI).vi`, `Login transmission (SubVI).vi`, `Login Status (SubVI).vi` - login-related modules
- `database.txt`, `purchaselog.txt` - text-based supporting data

## Tech Stack

- LabVIEW
- VI / SubVI modular design
- Text-file persistence for simple records

## Run

1. Open `Assignment.lvproj` in LabVIEW.
2. Load the required VIs and controls.
3. Run the main VI to start the automation flow.
