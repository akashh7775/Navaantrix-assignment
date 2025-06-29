# Task 2: File Listener

## Overview
This notebook demonstrates a script that monitors a directory for new files and uploads their content to a database.

## How to Use
1. Set the target folder path.
2. Define database connection settings.
3. Run the script to continuously monitor for new files.

## Code Explanation
- Uses `watchdog` or polling to monitor file changes.
- Connects to SQLite or any preferred database.
- Reads new CSV files and uploads to database.
- Error handling for invalid files or connection issues.

## Example Output
- Console output showing detected file and upload status.
- Data successfully inserted into a database table.
