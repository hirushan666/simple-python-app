# Simple Python Web App for SonarQube Cloud Analysis

This is a minimal Flask web application designed to be analyzed by SonarQube Cloud. It includes a basic endpoint and the necessary SonarQube configuration file.

## Features
- Minimal Flask app with a single route
- Ready for SonarQube analysis via `sonar-project.properties`

## Requirements
- Python 3.7+
- pip

## Setup

1. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
2. Run the app:
   ```sh
   python app.py
   ```

## SonarQube Analysis

When this project is pushed to GitHub, you can configure SonarQube Cloud to analyze it using the included `sonar-project.properties` file.

---
This project is intentionally simple for demonstration purposes.
