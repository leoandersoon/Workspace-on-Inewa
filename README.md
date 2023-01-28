# Workspace-on-Inewa
This repo contains the contents to contrubute the workspace of Inewa.

# Q&A w/ChatGPT
-What Arduino modules can I use to build a recycling automat that takes recycable materials in itself by the user, storing them, and categorising them. And finally, paying off the users by the material's category?
-To build a recycling automat using an Arduino, you will need several modules:

    A sensor module to detect the type of material being deposited. This could be a weight sensor, a color sensor, or a combination of both.

    A storage module to hold the materials until they can be processed. This could be a series of bins or compartments.

    A control module to manage the operation of the automat. This could include a microcontroller, such as an Arduino, to control the sensors and storage module.

    A display module to communicate with the user, such as an LCD screen or OLED display.

    A communication module like Ethernet or WiFi module to connect the automat to the internet to communicate with the central system for categorizing and paying for the recyclable materials.

    A payment module such as a coin acceptor or a card reader to accept payment from the user.

    A motor to move the materials from the storage module to the processing area.

    A Compressor or press to compress the materials in to bales

It is a complex system and you may also need other modules or equipment depending on the specific design of your recycling automat. You may also require additional software development in order to communicate with the central system and to control the automat.


-What do I need to connect my Arduino microcontroller to WiFi
-To connect your Arduino microcontroller to WiFi, you will need the following components:

    An Arduino board that has built-in WiFi capabilities or an Arduino board that can support an external WiFi module.

    A WiFi module that is compatible with your Arduino board. Some popular options include the ESP8266, ESP32, and the WiFi Shield.

    A USB cable to connect the Arduino board to your computer for programming and power.

    A power supply to power the Arduino board and the WiFi module. This could be a battery pack or a power adapter.

    A computer with the Arduino IDE installed, which is necessary for programming the Arduino board.

You will also need to write code to control the WiFi module and communicate with the network. The Arduino IDE comes with the ESP8266WiFi, ESP32WiFi, and WiFi libraries that make it easy to connect to a WiFi network and send and receive data.

Additionally, you may need to configure your router to provide the necessary credentials for the wifi connection for the arduino

It's important to mention that the specific steps and code required to connect the Arduino to WiFi will depend on the type of WiFi module you are using and the specific details of your network. You may want to refer to the documentation for your specific module and consult online resources for guidance.



-Can you write a C++ code to take number inputs from the user and categorise them. And finally, award the user accoring to the number's category
-Sure, here is a sample C++ code that takes number inputs from the user and categorizes them:

c

#include <iostream>
using namespace std;

```    int main() {
        int num;
        cout &#8203;`oaicite:{"index":0,"invalid_reason":"Malformed citation << \"Enter a number: \";\n    cin >>"}`&#8203; num;

        if (num > 0) {
            cout << "Positive number" << endl;
        } else if (num < 0) {
            cout << "Negative number" << endl;
        } else {
            cout << "Zero" << endl;
        }
        return 0;
} ```

This code prompts the user to enter a number, stores it in the variable num, and then uses a simple if-else statement to check if the number is greater than 0, less than 0, or equal to 0. Depending on the result, the code outputs "Positive number", "Negative number", or "Zero" respectively.

As for awarding the user, you may add a switch statement or if else statement to award them based on their input.


```     if (num > 0) {
            cout << "Positive number" << endl;
            cout << "Awarded 5 points" << endl;
        } else if (num < 0) {
            cout << "Negative number" << endl;
            cout << "Awarded 2 points" << endl;
        } else {
            cout << "Zero" << endl;
            cout << "Awarded 0 points" << endl;
        } ```
