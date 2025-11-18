# GreenLab

GreenLab is a system designed for laboratories, indoor green spaces, and
growing areas that require constant monitoring and regulation of plant
development. Its main purpose is to monitor environmental conditions in
real time, providing updated information to optimize maintenance and
ensure proper plant growth.

Additionally, GreenLab integrates an automatic hydration process that
allows plants to receive the exact amount of water they need at the
right time based on collected data and detected needs in each area.

## Roles

### Front-End

-   Santiago Comas
-   Daniel Chalarca

### Back-End

-   Fabián Beleño

### Data Analyst

-   Favián Caiafa

### Arduino / Hardware Developer

-   Joel Restrepo

### UI Designer

-   Santiago Comas
-   Daniel Chalarca

### Scrum Master

-   Santiago Comas

### GitFlow Master

-   Daniel Chalarca

## Scrum Methodology

All development tasks will be available in DevOps starting Tuesday of
each week. The team works in sprints and follows standard Scrum
practices.

## Project Details

**Team name:** ARK DevOps\
**Project name:** GreenLab\
**Repository guidelines:** GitFlow + Conventional Commits

## General Tasks

### Arduino / Hardware

-   Sensor reading on ESP32 microcontroller
-   Ultrasonic sensor distance reading
-   Motor activation through ultrasonic distance detection
-   Integration of LCD Display (20x4)
-   Implementation of an RGB LED driver
-   Development of a humidity sensor
-   Temperature and humidity sensor implementation
-   General hardware programming and communication with backend APIs

### Back-End

-   Creation of the main API
-   Implementation of ML tool and data analysis
-   Water level sensor integration
-   API routes for data manipulation
-   Machine learning model training and deployment
-   Backend communications for sensor reading and control

### Data Analyst

-   General data analysis
-   Sensor data analysis
-   Data processing for ML and prediction features

# GitFlow Documentation

## Branch Structure

The repository follows GitFlow to maintain an organized workflow:

### Main Branches

-   main → Production-ready code
-   develop → Integration of features before release

### Supporting Branches

-   feature/ → New features
-   fix/ → Bug fixes
-   hotfix/ → Critical fixes directly to production
-   release/ → Version preparation before merging into main

## Conventional Commits

### Types

-   feat: Adds a new feature
-   fix: Fixes a bug
-   docs: Documentation changes only
-   style: Code formatting (no logic changes)
-   refactor: Code rewrite without new features
-   test: Adding or fixing tests
-   chore: Non-production tasks (configs, dependencies)

### Examples

feat: add moisture sensor reading module\
fix: correct error in LCD display initialization\
docs: update project architecture diagram\
refactor: optimize API water-level controller
