# Deloitte Telemetry Data Standardization Pipeline

A Python-based telemetry processing pipeline built as part of the Deloitte Australia Technology Job Simulation.

## Overview
This project processes, cleans, and standardizes multi-source JSON telemetry feeds across manufacturing facilities into a unified schema with epoch millisecond timestamps.

## Features
- Dynamic JSON ingestion and transformation
- ISO 8601 string to epoch millisecond timestamp conversion
- Automated validation via Python's built-in `unittest` suite

## Usage
Run the test suite from your terminal:
```bash
python main.py
