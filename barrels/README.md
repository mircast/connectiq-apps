# Barrels
Monkey Barrels are a way for developers to create custom Monkey C libraries containing source code and resource information that can be easily shared across Connect IQ Projects. To find out more about Monkey Barrels, please see the <a href="https://developer.garmin.com/connect-iq/programmers-guide/shareable-libraries/">Shareable Libraries</a> chapter in the Programmer's Guide.

## Including Monkey Barrels
To include a Monkey Barrel in your project you need to declare a dependency on that Barrel within your Manifest file and then link to the Barrel within your project's Jungle file. See the [Programmer's Guide](https://developer.garmin.com/connect-iq/programmers-guide/monkey-barrels#how-to-include-barrels) for a detailed description of how to include Monkey Barrels in your project.

## Barrel Index

### **[LogMonkey](https://github.com/garmin/connectiq-apps/tree/master/barrels/LogMonkey)**
The LogMonkey barrel provides some basic logging utilities to aid in developing Connect IQ apps. Including LogMonkey within an app and building the app in release mode will automatically minimize the compiled output to save run time memory.

### **[Semicircles](https://github.com/garmin/connectiq-apps/tree/master/barrels/Semicircles)**
The Semicircles barrel provides an abstract coordinate type that speeds up position computation, does not use Position module, and does not require the Position permission. This class also includes a fast method to calculate the distance between two points.
