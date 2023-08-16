**ISS Tracker**

This is a Python script that uses various modules and APIs to display the current number and names of astronauts on the International Space Station (ISS), as well as the current location and movement of the ISS on a world map. It also shows the user’s current latitude and longitude using geocoder module.
Dependencies

The script requires the following modules to be installed:

    json
    turtle
    urllib.request
    time
    webbrowser
    geocoder

You can install them using pip or any other package manager.
Usage

To run the script, simply execute it in your terminal or IDE. It will create a text file named “iss.txt” that contains the information about the astronauts on the ISS and the user’s location. It will also open the text file in your web browser. Then, it will show a turtle graphics window with a world map and an ISS icon that moves according to its real-time coordinates. The script will update the ISS location every 5 seconds and print its latitude and longitude in the terminal.
APIs

The script uses the following APIs to get the data:

    Open Notify - an open source project that provides various APIs related to space and NASA.
    Geocoder - a Python library that makes it easy to get geocoding information from various providers.

**License**

This script is licensed under the MIT License. See LICENSE for more details.
