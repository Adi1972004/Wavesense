WaveSense: Microcontrollers-based Waveform Generation and Frequency Measurement
WaveSense is an atypical project which generates specific waveforms with the help of a microcontroller-ATmega32, with frequencies predetermined by the user, and measures the frequency of the input signals. The project involves hardware design and embedded C to provide flexible signal generation and analysis. It can also be helpful in clock generation, amplification of signals, and frequency measurement; hence, finding its usage in many areas related to electronics and communications.

Key Features:
The tasks will also involve generating waveforms-square, sine, and triangular-using onboard timers and PWM of the ATmega32 microcontroller. This also involves precise frequency measurement of an incoming signal by using input capture. The frequency of the waveform should be exhibited on a 16x2 alphanumeric LCD, communicating with the microcontroller via the I2C protocol. In the signal amplification stage, the sine and triangular waves are amplified.
Software Simulation & Hardware Integration: Circuit designs will be simulated with Proteus software and then code writing/debugging will be done in Atmel Studio before deployment on hardware.
Tools and Software
Atmel Studio: This is the IDE to be used for writing, compilation, and debugging of the embedded C code.
Proteus: Electronic design automation tool used for the simulation of the microcontroller circuit.
eXtreme Burner: Code will be uploaded through this onto the microcontroller via a USBASP programmer.
Components
ATmega32 Microcontroller
16x2 LCD Display
USBASP Programmer
PCF8574T Port Expander (I2C)
Buck Converter
Applications
Digital clock generators
Signal prediction and measurement systems; Waveform amplification for communication systems
