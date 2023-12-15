Weather prediction, also known as weather forecasting, is the process of estimating the state of the atmosphere at a specific location for a given period in the future. It involves analyzing current atmospheric conditions, such as temperature, and humidity. Meteorologists use computer models that simulate the behavior of the atmosphere to make predictions about future weather conditions. While short-term forecasts (up to a few days) are generally more accurate, long-term predictions involve greater uncertainties. Advances in technology, satellite observations, and numerical modeling have improved the accuracy of weather predictions over time.

Hardware Requirement:
   * NodeMCU
   * DHT11/DHT22
   * breadboard
   * Jumper Wire

Software Requirement:
   * Arduino IDE

Circuit Diagram
![circuit](https://github.com/om-1980/Weather-prediction-/assets/111452597/f705196e-018c-49f0-8172-8661d21f1210)


1. Install Library File
   * Add TRIGGER_LIBRARY to path "C:\Users\Documents\Arduino\libraries"
   * Open your Arduino IDE and go to Sketch > Include Library > Manage Libraries. The Library Manager should open.
   * Search for “DHT” in the Search box and install the DHT library from Adafruit.
   *After installing the DHT library from Adafruit, type “Adafruit Unified Sensor” in the search box. Scroll down to find the library and install it.
   * After installing the libraries, restart your Arduino IDE

2. Setting Google Sheet
   * Make a Blank Spreadsheet
   * Name the sheet
   * Make column1 as 'Date' and column2 as 'Time' and the rest column as per your parameter
   * If this is the link for Google Sheet "https://docs.google.com/spreadsheets/d/1t_fZLuPXjuXmRy38pivTYQNfdQ-yfi8u65dDoczBOkM/edit#gid=0" then spreadsheet is "1t_fZLuPXjuXmRy38pivTYQNfdQ-yfi8u65dDoczBOkM" in between spreadsheets/d and edit#gid=0

3. Setting Script
   * Go to Extension > Apps Script
   * Name Apps Script same as Google Sheet
   * Paste the script.txt code in Apps Script 
   * Change the spreadsheet to link Google sheet to the script
   * Change the parameter according to your necessary
   * Now Go to Deploy>New Deployment, select 'Web app'
   * Write the description according to you (not necessary) and make access from myself to anyone
   * After clicking on Deploy a pop-up display will open with the URL, copy that URL.
   * Url is helpful to find 'gas id' and add the values manually by pasting the url+?parameter1=value1&parameter2=value2 and so on like this https://script.google.com//macros/s/AKfycbxJOVmQq09JhYH_clqg6_fhnOj3SZic6WjjeNHmIEd18aC-ik2fIS4lwR8Sy96t2g7iWg/exec?Temperperature=24.00&Humidity=49.80, and "AKfycbxJOVmQq09JhYH_clqg6_fhnOj3SZic6WjjeNHmIEd18aC-ik2fIS4lwR8Sy96t2g7iWg" is your gas id in between macros/s and /exec?

4. Setting the Arduino IDE
    * Change the WIFi credentials and parameters according to you
    * Now, upload the code and analyze the data generated. 
5. Output
   ![image](https://github.com/om-1980/weather-prediction-/assets/111452597/b6e115e2-8392-4bcb-ae61-a959c4621f10)

    
