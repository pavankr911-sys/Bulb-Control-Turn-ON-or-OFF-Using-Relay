​💡 Microcontroller-Based AC Bulb Control with Relay
​This project demonstrates a fundamental application in automation: safely controlling a high-voltage AC appliance (a standard light bulb) using a low-voltage digital signal from a microcontroller (like an Arduino). [cite_start]This system is a core building block for Smart Home and Industrial Control solutions[cite: 3].
​

🎯 Objectives & Key Principles
​[cite_start]Objective: To interface a microcontroller with a relay module to safely switch a high-voltage AC load ON or OFF[cite: 2].
​[cite_start]Core Principle: Relays provide essential electrical isolation between the low-power control side and the high-voltage AC power side[cite: 44, 81].
​[cite_start]Transistor Driver: A transistor is used as a driver/electronic switch, as the microcontroller's digital output is too weak to directly energize the relay coil[cite: 42, 52].
​[cite_start]Protection: A flyback diode is crucial for suppressing damaging voltage spikes (Back EMF) generated when the relay coil is de-energized[cite: 34, 47, 55].
