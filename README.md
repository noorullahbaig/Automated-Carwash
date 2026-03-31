# Automated Carwash

## Overview

Automated Carwash is a LabVIEW project that models a touchless car wash workflow with login handling, operational control logic, and simple file-backed records. The repository contains the main project file, separate primary VIs, supporting subVIs, and text files used for stored data.

## Features

- LabVIEW project structure centered on a main car wash workflow
- Separate server-side VI included in the repository
- Login validation, transmission, and status subVIs
- Text-backed storage for account and purchase information
- Modular controls and supporting LabVIEW assets

## Tech Stack

- LabVIEW
- VI / SubVI modular design
- Text-file persistence

## Project Structure

- `Assignment.lvproj` - main LabVIEW project file
- `Assignment.vi` - primary workflow VI
- `Assignment server.vi` - supporting server-side VI
- `Login Validation (SubVI).vi`, `Login transmission (SubVI).vi`, `Login Status (SubVI).vi` - login-related modules
- `Control 1.ctl`, `Control 2.ctl`, `Control 1 server.ctl` - shared control definitions
- `database.txt`, `purchaselog.txt` - stored text records

## How to Run

1. Open `Assignment.lvproj` in LabVIEW.
2. Load the main VI and any required supporting VIs or controls.
3. Run the workflow from the project, using `Assignment.vi` as the primary starting point.
