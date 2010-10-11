# KeypadIgnition #

KeypadIgnition is an electronics project that will allow me to start my car, Sylvia, by entering a passcode, as oppose to starting her the boring, "traditional" with a key. (In other words, it'll make me feel like a secret agent whenever I hop in my car, punch in a keycode, and have it roar to life. How bad ass would that be? ;-)

## Project status

** Work in-progress **

## Background

I had an old [BASIC Stamp](http://en.wikipedia.org/wiki/BASIC_Stamp) microcontroller laying around, and thought I'd put it to use. After finally getting the [compiler](http://www.parallax.com/tabid/441/Default.aspx) working on my Linux laptop with [Wine](http://www.winehq.org/) (see the "Technical notes" section below), I did a few tests, and determined it would probably work for the project.

## Images

 - [Physical keypad unit (so far)](http://twitpic.com/2urter)
 - [Circuit diagram (most-recent design)](http://twitpic.com/2wilea)
 - [Measuring current of existing ignition switch modes](http://twitpic.com/2w72s6)

## Technical notes

### The BASIC Stamp Editor and Wine under Linux

Getting the BASIC Stamp Editor working under Linux was paramount to making this project possible (mainly because I was too lazy and stubborn to install Windows). Success was finally made after reading [this post](http://ubuntuforums.org/showthread.php?t=1523814). I followed it almost exactly, except there was no need to follow the "VERY IMPORTANT STEP", I'm guessing because the bug he was referring to doesn't exist in the newer version of Wine I'm using. Speaking of which, I am using the following versions:

 - ** Wine v1.1.42 **
 - ** BASIC Stamp Editor v2.2 **

### About the microcontroller (MCU)

I'm using a BASIC Stamp 2, which uses the [PBASIC language](http://en.wikipedia.org/wiki/PBASIC). You can read all about the BASIC Stamp 2 [here](http://en.wikipedia.org/wiki/BASIC_Stamp).

### About my car

Her name is Sylvia, and she's a 2001 Subaru Impreza L Sports Wagon ("Sports Wagon"? Kind of an oxymoron, eh? ;-)

