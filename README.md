# BATPOWER04 - Step-down Voltage Converter Module

BATPOWER04 is a step-down voltage converter module based on the [LM3485](doc/pdf/lm3485.pdf) PFET buck controller. The input voltage range is 4.5 V to 16 V. The output voltage can be selected by jumpers as 3.3 V or 5 V, or configured as a custom voltage using an external resistor or trimmer. The output voltage range is 0.25 V to Vin.

The module is especially suited for battery-powered applications, but it can also be used as a step-down converter from an external 12 V supply to 3.3 V or 5 V for MLAB designs. Its key feature is high efficiency, up to 93%, which helps reduce waste heat.

![BATPOWER04 module](/doc/img/BATPOWER04C_top_big.jpg)


| Parameter | Value | Description |
|-----------|-------|-------------|
| Step-down controller | [LM3485](doc/pdf/lm3485.pdf) | PFET Buck controller |
| Vin | 4.5 V - 16 V | Input voltage range |
| Vout | 0.25 V - Vin | 3.3 V or 5 V selectable by jumper. Other values require an external resistor or trimmer. |
