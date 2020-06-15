# Smartglove-for-Cyclists

![Smart-gloves](/images/smartgloves)

__How it works:__

The glove is made with an Arduino board that collects data from a gyroscope and an accelerometer. The Arduino code uses a model of tiny machine learning (tinyML), and it works with gesture recognition: each hand movement is analyzed and recognized (hand tilted to the left, right, front, back, etc.). Then this signal is sent through Bluetooth (BLE) to another microcontroller connected to an LED matrix (placed on a backpack, for example). According to the signal received by the microcontroller, some patterns light up on the LED matrix, so that other road users can see what the cyclist is doing (as an example right, left and straight arrows, or also text).

__Origins of the project:__

This is what motivated me to make this project:

First, I go to work by bike, and I ride more than 1 hour every day (approximately 22 km). This is always a lot of fun, except that I live in one of the most crowded cities in France, and incidents between cars and cyclists are frequent. This is especially true since Marseille is the worst city for cyclists (in France), with a huge lack of bicycle tracks (as you can read here). Therefore, this is a project to improve cyclist safety, but also to report the lack of consideration from the city toward cyclists.
Second, it is a project to help road users to communicate and understand each other better. In my point of view, most incivilities I see between road users are due to the fact that some users misinterpreted the behavior of the others, scaring them and leading to aggressiveness. With this device I want road users to understand each other better: arrows indicate the direction, and text can be displayed (but I strictly stick with nice and constructive text, to avoid starting conflicts).
Why is it called "smartglove"?
I initially started this project in winter, and cold weather was what motivated me to make this device on a glove. But I quickly realized it was a bad idea since it is quite hot in summer here. So placing this device in a box, and attach it to the hand was the perfect solution. But how to call such a device? Since I had no clue about a new name, I kept the term "glove", and there we are!

"Smart" comes from the tiny machine learning technique used for this project.

__Inspirations:__

This project is a mix of 2 main projects I found. I did not start from scratch but rather took advantage of these projects to go further and make a more advanced one. These are the projects I got inspiration from:

- The gesture recognition with Arduino Nano 33 BLE SENSE, that you can read by clicking here.
- The other source of inspiration is not a specific project, but rather the concept of LED panels for cyclists. There are a lot of such projects, some are backpacks with integrated LED matrix, some others just consist in a matrix that can be attached anywhere. But in all cases, these LED panels are controlled with a remote (and not gesture recognition).

__Supplies:__

![Supplies](/images/smartglovesupplies.jpg)

For 3D printed parts:

- A 3D printer, or access to a fablab or online 3D printing service;
- PLA.

__For electronics parts:__

- An Arduino Nano 33 BLE SENSE;
- Another microcontroller with BLE (Arduino Nano 33 BLE, Arduino 33 BLE SENSE, Arduino nano 33 IOT, ESP32, etc.). I decided to use an ESP32 board as I will explain later;
- LED strip (WS2812B). I used 160 LEDs, to make a LED matrix of 20x8;
- A quad-level shifter 3V to 5V: 74AHCT125;
- A 1000 microF capacitor;
- SPST switches (x3);
- Perfboards;
- Wires and jumper wires;
- A 9V battery;
- A power bank.

__Other:__

- M3 screws and nuts;
- Hook-and-loop fastener.

[Credits/Source](https://www.instructables.com/id/Smartglove-for-Cyclists/?utm_source=newsletter&utm_medium=email)
