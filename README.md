**# AC-Dimmer-using-TRAIC**
  This project illustrates an AC dimmer circuit that uses phase control to regulate the amount of power supplied to an AC load, such as a motor, fan, or lightbulb, where the conduction 
  angle of the AC waveform is adjusted using a variable resistor (POT).

**# Components:**
• Triac (BTA16F): Acts as the main switch, controlling the power delivered to the load.
• Diac (C89621): Provides a triggering pulse to the gate of the Triac.
• Resistors (R1 and R2): Limit current and provide a voltage divider network.
• Potentiometer (POT, 500K): Allows the user to adjust the phase angle of the AC waveform.
• Capacitors (C1 and C2, 100nF): Form an RC timing circuit for smooth phase angle adjustment.
• AC Load: The device being controlled (e.g., a lamp or motor).
• 230V AC Supply: Input power for the circuit.


**#Circuit Operation**
• The RC network delays the phase of the AC voltage.
• The capacitor charges until the Diac triggers the Triac.
• The Triac controls the current flow to the load based on the phase angle.
• Adjusting the potentiometer changes the phase delay, altering the power delivered to the load.
