Weather prediction, also known as weather forecasting, is the process of estimating the state of the atmosphere at a specific location for a given period in the future. It involves analyzing current atmospheric conditions, such as temperature, and humidity.

Hardware Requirement:
   * NodeMCU
   * DHT11/DHT22
   * breadboard
   * Jumper Wire

Software Requirement:
   * Arduino IDE

Circuit Diagram
   ![circuit](https://github.com/om-1980/Weather-prediction-/assets/111452597/c81c411f-8967-41a3-9a85-86edc9812ddd)


1. Setting Up ThingSpeak
    * Create New Channel
    * Go to API Keys section and copy the "Write API Key"

2. Install library files
    * Open your Arduino IDE and go to Sketch > Include Library > Manage Libraries. The Library Manager should open.
    * Search for “ThingSpeak” on the Search box and install the thingSpeak library from MathWorks.
    * After installing the library, restart your Arduino IDE

3. Setting the Arduino IDE
    * Change the API key and WIFi credentials
    * Now, upload the code and analyze the graph generated
  
4. Output
   ![image](https://github.com/om-1980/weather-prediction-/assets/111452597/7d3cd2b4-babf-4c2c-aec3-45c063b080e3)
   ![image](https://github.com/om-1980/weather-prediction-/assets/111452597/5b01fba0-46f1-4a2e-bea1-cbbfad16704d)


