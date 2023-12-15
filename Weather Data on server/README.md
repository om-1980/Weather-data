Weather prediction, also known as weather forecasting, is the process of estimating the state of the atmosphere at a specific location for a given period in the future. It involves analyzing current atmospheric conditions, such as temperature, and humidity.

Hardware Requirement:
   * NodeMCU
   * DHT11/DHT22
   * breadboard
   * Jumper Wire

Software Requirement:
   * Arduino IDE

Circuit Diagram
 
![circuit](https://github.com/om-1980/Weather-data/assets/111452597/6d3df60f-1fab-4c38-a30b-8edb0b7979a2)



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
   
![Screenshot 2023-12-14 165007](https://github.com/om-1980/Weather-data/assets/111452597/183d0e1b-d455-4089-815a-ee5f7cba1de5)


![Screenshot 2023-12-14 165056](https://github.com/om-1980/Weather-data/assets/111452597/bf07db65-fb58-4349-8f18-aa0eb81d1ee5)
