Random_Circuits
===============

Random Compatible Circuits Project

I wanted to produce a series of electronic circuits that all work together, were you to provide adequate power and connect via the appropriate bus to an MCU.  This is just the start of this project so there is quite a bit more to come.  A few top-level notables:

All circuits are (unless stated otherwise)...

- Designed to run at 3.3 volts
- Designed to utilize either I2C or SPI interfaces (and the occasional GPIO where required)
- Operate as "plug and play" (even with respect to net names)

You will notice some things that are prerequisties to making this stuff work in this way...

- Firstly, net names need to be normalized lest netlisters or schematic / PCB tools leave parts of the circuit disconnected (5V is very different than +5.0V is different than 5V0...thus to get this right, nets need to be normalized to simplified names for things to work)

- Secondly, all documents adopt a standardized sheet to sheet connectivity schema (i.e. flat, hierarchical, etc).  

More details to come... :)  (note: this is a work in progress and the contents of this project are not warrantied and carry no guarantee as to suitability, what-not.  Electronics can kill.  Be careful and be sure to evaluate and test any circuits you see here, before you decide to build them.  If you do not, you may be injured and I do not guarantee that any of this stuff actually works.
