# MPC-CONTROLLING-OF-ELECTRICAL-APPLIANCE-USING-LAPTOP

We are controlling a Relay Module by Arduino using Serial communication with the laptop. 
We can switch on and off the light using our laptop. We would be making use of Relay­6V and Arduino board­ATMEGA 328.We will be making an interface through which the user can either click on/off button (on the laptop screen),and this is interpreted by the Arduino using serial communication. If the data received is a "1”,set the third pin high, and the bulb will glow otherwise it will be put off. The components will interact with each other through a processing language­JAVA.


    HARDWARE IMPLEMENTATION

        •	Microcontroller-Arduino Uno-ATMEGA 328.
        •	Relay 6V.
        •	BJT (NPN)–BC 547.
        •	Diode-4007.
        •	Bulb.
        •	Adaptor 6V.


    SOFTWARE IMPLEMENTATION
    
        •	Arduino.
        •	Processing.


    DESCRIPTION OF HARDWARE    
       • ARDUINO:
            The Arduino Uno is a microcontroller board based on the ATmega328 . It has 14 digital input/output pins (of which 6 can be used as PWM outputs), 6 analog inputs, a 16 MHz ceramic resonator, a USB connection, a power jack, an ICSP header, and a reset button. It contains everything needed to support the microcontroller; simply connect it to a computer with a USB cable or power it with a AC-to-DC adapter or battery to get started.
     
        • RELAY:
            Relay is an electromagnetic device which is used to isolate two circuits electrically and connect them magnetically. In our project it has allowed one circuit to switch another one while they are completely separate. 
     
        • BJT-BC547
            BC547 is an NPN bi-polar junction transistor. The voltage divider is the commonly used biasing mode. In this project we have used the transistor for switching purposes.For these switching applications, transistor is biased so that it remains fully on if there is a signal at its base. In the absence of base signal, it gets completely off.
    
        • Diode-4007
            The most common function of a diode(for which we have used it as well) is to allow an electric current to pass in one direction (called the diode's forward direction), while blocking current in the opposite direction (the reverse direction). Thus, the diode can be viewed as an electronic version of a checkvalve. This unidirectional behavior is called rectification.

    RESULTS AND CONCLUSIONS
        We are now able to control the glowing of the bulb through our laptop which had the user interface of a switch board( the ON/OFF button). This saves a lot of time and electricity.
