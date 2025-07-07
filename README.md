# KiwiEFI-K88-ECU-Speeduino-Compatible
TEENSY3.5/3.6 BASED ECU USING SPEEDUINO FIRMWARE.

![K88ecu](https://github.com/Neil427/KiwiEFI-K88-ECU-Speeduino-Compatible/assets/67580691/b6c15399-bfd3-4c67-b95c-0dc14941cbda)

NOTE:	THESE FILES ARE FOR A ECU USING THE TEENSY3.5/3.6 MCU MODULE 
	WHICH IS DISCONTINUED AND EXTREMELY DIFFICULT TO FIND.
	DO NOT SPEND MONEY HAVING THIS BOARD MANUFACTURED UNTIL YOU 
	FIRST PURCHASE THE TEENSTY MODULE!
.
.
THESE FILES ARE PUBLISHED TO PROVIDE DOCCUMENTATION AND SUPPORT TO THE EXISTING OWNERS OF THE K88 ECU.
.
.
.
I will not be upgrading it to Teensy 4.1 however I have included all the Kicad design files for anyone who wishes to attempt this.
.
.
{
IF YOU ARE GOING TO MAKE A K88 PLEASE NOTE: 
1- THE PNP FILE FOR THE K88 IS ONLY FOR THE TOP SIDE AND DOES NOT INCLUDE THE SWITCHES, 6x DIGITAL OUTPUT DRIVERS, LOADDUMP PROTECTION COMPONENTS, AND THE THROUGHHOLE COMPONENTS. I hand fitted these parts as they were not available at JLC.
2- THE IGNINJ SUBBOARD AND MAP1 SUBBOARD HAVE NO PNP FILE as they were hand assembled.
}




The KiwiEFI K88 is a high speed Teensy 3.5 powered Ecu which is 100% compatible in software configuration with the Speeduino Dropbear Ecu with a few important enhancements:

    - A 56-pin connector which allows the simultaneous use of stepper idle control and all of the digital outputs, i.e. you don't lose 4x outputs if you require stepper idle control.

    - Serial output to the Ecu connector which can be switched between TTL level  or RS232 level for connecting external devices like dashes etc.

    - Socket for a Crank/Cam VR conditioner allowing use of any brand of conditioner, not just the Max9926.

    - Socket for a second VR conditioner on Digital Input 1 and 2 with switchable filtering, for use with VVT cam sensors or VR speed/ wheel speed sensors. 

    - On board Map sensor can be either SMD MPXHZ6250 type sensor,  or MPX4250 through hole type sensor, or a KiwiEFI vertical solder in board with a SMD sensor.


 

K88 Features
       	8x high impedance injector drivers  (with diagnostic indicator LEDs)
       	8x 5v/12v coil pre-drivers for use with igniters/smart coils  (with diagnostic indicator LEDs)
       	2x low current outputs for Fuel Pump relay and Tach (with diagnostic indicator LEDs)..
       	4x medium current outputs for Boost, Idle1, Idle2, Fan relay. 
       	2x high current outputs for VVT solenoids;
       	4x outputs dedicated to Stepper idle control (using optional DRV8825 board)
       	7x analog inputs plus internal Barometric Pressure Sensor and Battery Voltage sense inputs
       	4x digital inputs (2 with optional VR conditioner and filtering).
       	CAN transceiver with termination jumper option 
       	Serial Data with switch selection of 3.3V-TTL or RS232 voltage levels (with TXD indicator LED)
       	Optional plug-in VR conditioner for Cam/Crank sensors,
       	Onboard Hall type Crank/Cam sensor conditioning and isolation diodes
       	Switch selectable filtering on Crank and Cam triggers,
       	Diagnostic LEDs for CRANK, CAM, DI1 and DI2 inputs.
       	Optional internal Map sensor or external sensor (we recommend external for faster response)
       	4x LED indicators for power supply voltages status
	Internal datalogging to MicroSD card









