## Overview

As a software engineer, I've always wanted to dive into electronics and hardware but never really found the right motivation. After discovering the [GitHub Stoplight Project](http://urbanhonking.com/ideasfordozens/2010/05/19/the_github_stoplight/), I found my motivation.

This repository is my journal for trying out electronics by implementing my own version of the GitHub stoplight using an Arduino.

## Algorithm
The algorithm of the stoplight controller is pretty simple:

1. Process input from either the manual keypad or a REST PUT request through the Ethernet shield.
2. Execute the instruction(s) from step (1).
3. Display the status on the RGB LCD sreeen

## Parts List
* [Arduino Uno R3](https://www.adafruit.com/products/50)
* [Arduino Ethernet Shield](https://www.adafruit.com/products/201)
* [Adafruit RGB LCD Display Kit](https://www.adafruit.com/products/714)
* [SainSmart 4-Channel Relay Board](http://www.amazon.com/gp/product/B0057OC5O8)
* [Adafruit Arduino Panel](https://www.adafruit.com/products/275)
* [Half-size Breadboard](https://www.adafruit.com/products/64)
* [Panel Mount Ethernet Extension Cable](https://www.adafruit.com/products/909)

## Notes
* __Arduino Ethernet__ - I used a separate Arduino Uno R3 + the Ethernet shield, which was a little overkill. I would recommend the Arduino Ethernet for a single, compact offering.
* __Raspberry Pi__ - I would also look at using the Raspberry Pi, which may be my next adventure.

## Pictures
Everybody loves pictures.  They will go here.

## References
* [GitHub Stoplight Project](http://urbanhonking.com/ideasfordozens/2010/05/19/the_github_stoplight/)
