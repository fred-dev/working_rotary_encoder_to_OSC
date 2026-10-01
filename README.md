# working_rotary_encoder_to_serial

Arduino sketch that reads a quadrature rotary encoder on interrupts and sends its position (in degrees) over OSC via an Ethernet shield. Despite the name, output is OSC, not serial.

## Needs

- Arduino with an Ethernet shield, encoder on pins 2 and 3
- Libraries: `digitalWriteFast`, `Ethernet`, `ArdOSC`
- Set `myIp`, `destIp` and `destPort` (default 12000) in the sketch

Old code (2013), kept for reference.
