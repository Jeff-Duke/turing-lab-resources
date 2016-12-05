# Getting Started with NodeBots

## What is a NodeBot?
The term NodeBot refers to any hardware controlled by JavaScript.  For us this means using the [Johnny-Five](http://johnny-five.io/) library with a [microcontroller](https://en.wikipedia.org/wiki/Microcontroller).  The advantage of using Johnny-Five is that we can write our project code once and run it on the [vast majority](http://johnny-five.io/platform-support/) of microcontrollers available.

## Installing Johnny-Five
To install the Johnny-Five library you'll first need to [Install Node](https://nodejs.org/en/download/package-manager/#osx)

Once you have node installed you can use the Node Package Manager (npm) to install Johnny-Five:
`npm install johnny-five`

If you're using an Arduino system you'll also need to install [Firmata](https://github.com/firmata/arduino).  Firmata is a protocol for communicating with microcontrollers from a host computer.  This lets you use something other than the Arduino IDE to read/write to the microcontroller.  One great way to do that is with [Firmata Party](https://github.com/noopkat/firmata-party).

Now that you have your environment setup, a good first project is [Hello World](http://johnny-five.io/#hello-world).

## Where to go next:

[Johnny-Five Examples](http://johnny-five.io/examples/)

[Sparkfun Tutorials](https://learn.sparkfun.com/tutorials): Specifically the tutorials for the 
[Johnny-Five Inventor's Kit](https://learn.sparkfun.com/tutorials/experiment-guide-for-the-johnny-five-inventors-kit). (Note: The Johnny-Five Inventor's kit guide is written for the Tessel-2 microcontroller.  You'll need to keep this in mind when configuring the pinout for your components)

[Johnny-Five Articles](http://johnny-five.io/articles/)

## Where to go for help
If you're stuck on an issue it's important to identify if it's a problem with the microcontroller itself, how the components are connected or if it's an issue with the code. For issues with the microcontroller, refer to the manufacturer's website.  Often they have a robust support community and forums.  For Johnny-Five related issues check out the [Johnny-Five Gitter](https://gitter.im/rwaldron/johnny-five).



