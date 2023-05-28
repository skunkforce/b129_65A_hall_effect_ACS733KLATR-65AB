# low current test
## setup
Connect USB to supply 3.3V. Connect a lab power supply and a high current variable resistor through the terminal blocks.
```mermaid
flowchart LR 
  usb[USB] --> b051[b051 v1.0]
  b051 --> b103
  b103 --> b129
  power[Power SUpply] --> b129
  b129 --> r[Variable Resistor]
  
 ```
Measured the analog outputs while varying the current by changing the variable resistor.
## results
The 20mV per Amp could be verified on all 3 analog outputs.

