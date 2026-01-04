# robot-scripts

Robot Framework automation project for UI and API testing.
This repository follows a clean, beginner-friendly, and CI-ready structure for Robot Framework automation.

---

## Setup & Dependencies

This project provides **two supported ways** to install required Robot Framework libraries.

---

## externallib.bat (Windows – Local Setup)

**Location**
CRM/custom_libraries/externallib.bat

### Purpose
A Windows batch script to quickly install all required Robot Framework dependencies for local development.

### When to use
- Running automation locally on **Windows**
- Quick setup for new team members and Manual installations

### Usage
Run the script from Command Prompt or Git Bash: externallib.bat

## requirements.txt (Recommended – Cross Platform)
**Location**
CRM/custom_libraries/requirements.txt

### Purpose
Standard Python dependency file used for consistent, repeatable, and cross-platform installations.

### Usage
CI/CD pipelines

Command: pip install -r requirements.txt

### Recommended
Use requirements.txt for automation pipelines and professional setups
Use externallib.bat for quick local Windows setup

