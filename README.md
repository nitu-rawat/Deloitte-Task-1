# Deloitte Task 1 - Telemetry Data Conversion

## Overview
This project is a solution for Task 1 of the Deloitte Australia Virtual Experience Program.

The objective is to convert two different telemetry data formats into a single unified JSON format and ensure that all automated tests pass successfully.

## Files

- `main.py` - Contains the conversion logic and unit tests.
- `data-1.json` - Telemetry data in Format 1.
- `data-2.json` - Telemetry data in Format 2.
- `data-result.json` - Expected unified output format.

## Features

- Converts Format 1 telemetry data into the required unified format.
- Converts Format 2 telemetry data into the required unified format.
- Converts ISO 8601 timestamps to milliseconds since epoch.
- Includes automated unit tests for validation.

## How to Run

```bash
python main.py
