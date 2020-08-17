# ROV
These arduino files were used for the Linn-Benton Remotely Operated Vehicle (ROV) Team. The ROV is an underwater remotely operated vehicle that was created for the MATE ROV
international competition in Kingsport, Tennessee. The programs are meant to run on two different arduino unos. The master arduino recieves input from a playstation 2 controller
and sends it to through a cat5 cable to the slave arduino using UDP. The master arduino also recieves sensor information from the slave and displays it on the serial monitor.
The slave recieves the playstation 2 commands and interfaces them with the 6 thrusters, temperature sensor, pH sensor, mini-ROV, and electromagnet. These two files consist of
the entire program for the competition.
