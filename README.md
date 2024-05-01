Ignition Weather App

This script provides current weather data for integration into your Ignition SCADA projects.

Features:

    Retrieves real-time weather information.
    Optimized for use with Ignition's Perspective designer tags.

Installation:

    Import Tags:
        In your Ignition designer, navigate to the desired project or group.
        Import the provided weather tags (.tag files) into the project or group.

    Add Script:
        Open the Gateway Scripts section within Ignition.
        Create a new Timer Script that executes at your preferred interval (e.g., every 30 seconds).
        Paste the code from Script.py into the script editor of the timer script.

Usage:

Once the script and tags are configured, you can directly reference the weather tags in your Ignition project, such as:

    Displaying current temperature on a Perspective label.
    Triggering actions based on weather conditions (e.g., adjusting building temperature control).

Customization:

    The script can be modified to fetch additional weather data points (e.g., humidity, wind speed) by updating the API request and tag definitions.
    Consider implementing error handling in the script to gracefully manage potential API issues.

Prerequisites:

    Ignition SCADA platform.
    Python 3 (for script execution).
    External weather data API (specific API integration not included in this script).

Getting Started:

    Obtain API Key:
        Register for a free API key from a reputable weather service provider like OpenWeatherMap or Dark Sky (API integration details are outside the scope of this script).

    Update Script.py:
        Replace the placeholder YOUR_API_KEY with your actual API key in the script.

    Reference Tags:
        Utilize the imported weather tags in your Ignition project to display or utilize weather data.

Disclaimer:

This script is provided as a basic example and may require further development to suit specific project requirements. It's recommended to consult the documentation of your chosen weather service API for detailed integration instructions.

Contributing:

Feel free to submit pull requests to improve this script's functionality or documentation.
