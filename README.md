# workout_tracking_using_google_sheets

This project is an Exercise Tracking script that integrates with the Nutritionix API and Google Sheets API to automatically log exercise data based on user input. The script prompts the user to input exercises they've completed and then calculates relevant data such as calories burned, exercise duration, and type of exercise. The data is then sent to a Google Sheets endpoint to store the exercise log.

## Features
- Fetches exercise data using the Nutritionix API based on natural language input.
- Automatically logs exercise details like type, duration, and calories burned into Google Sheets.
- Uses environment variables to keep sensitive information secure.

## Setup
1. Clone the repository.
2. Set up environment variables:
   - `NT_APP_ID` and `NT_API_KEY` for Nutritionix API.
   - `SHEET_ENDPOINT` for the Google Sheets API endpoint.
   - `TOKEN` for authorization.

## How It Works
1. The script takes user input about exercises.
2. Sends data to Nutritionix API, which returns exercise details.
3. Logs the exercise data into Google Sheets via an API endpoint.

## What I Learned
- **API Integration:** Learned how to connect with external APIs, handle requests, and process JSON responses.
- **Environment Variables:** Implemented environment variables for secure handling of sensitive data.
- **Datetime Module:** Used the `datetime` module to format dates and times.
- **HTTP Headers & Bearer Token Authentication:** Gained hands-on experience with headers and authorization tokens.

## Dependencies
- `requests` (for HTTP requests)

## Example
### input:
  ![image](https://github.com/user-attachments/assets/f0d919bc-b671-48c3-a2ce-b9c3f444dd37)
### output:
  ![image](https://github.com/user-attachments/assets/764e4b33-f933-4a8d-91fe-9e31d3843162)
