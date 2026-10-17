---
title: Module's Selected Major Components
---

## Module's Selected Major Components

# Components

## Control LED Array

| Solution | Description | Pros | Cons |
|---|---|---|---|
| [SN74HC595](https://www.digikey.com/en/products/detail/texas-instruments/SN74HC595N/277246) | Option 1: SNx4HC595 — $1.83 each | Can turn on each LED individually. Can control a larger array of LEDs. | Limited LED power available. Must be used with other components to meet design needs. |
| [MOSFET 2N7000](https://www.digikey.com/en/products/detail/dcomponents/2N7000/13575174) | Option 2: 2N7000 MOSFETs — $1.09 each | Fewer components means less error prone. Very reliable product. Easy to design and implement. | Less control over individual LEDs. |
| **Selection** | **MOSFET 2N7000** | **Rationale** | Individual MOSFETs will allow the control of a string of LEDs and are rated for the current and voltages needed. The PIC has enough control outputs that the register is unnecessary and overly complicated. |

## LED Array

| Solution | Description | Pros | Cons |
|---|---|---|---|
| [C5SMF-RJF-CT0W0BB2](https://www.digikey.com/en/products/detail/cree-led/C5SMF-RJF-CT0W0BB2/4794052) | Option 1: C5SMF-RJF-CT0W0BB2 — $0.21 each | Correct form and specs for application. Red can simulate the sunrise/sunset desired for the design. Fairly reliable product that is readily available. | Single LED color selection will not provide enough for the ambient lighting design. Low lumen output. |
| [C5SMF-GJE-CX14Q7T2](https://www.digikey.com/en/products/detail/cree-led/C5SMF-GJE-CX14Q7T2/4794039) | Option 2: C5SMF-GJE-CX14Q7T2 — $0.36 each | Correct form and specs for application. Can help create a calming earth-tone mood lighting as designed. | Single LED color selection will not provide enough for the ambient lighting design. Voltage needed is slightly higher than other options. |
| [C5SMF-BJF-CR0U0351](https://www.digikey.com/en/products/detail/cree-led/C5SMF-BJF-CR0U0351/4793781) | Option 3: C5SMF-BJF-CR0U0351 — $0.23 each | Correct form and specs for application. Blue light can create an underwater or blue-sky effect when indoors. | Single LED color selection will not provide enough for the ambient lighting design. Lumen output is low. |
| **Selection** | **All three LEDs will be used** | **Rationale** | Each LED will provide a different color. This will allow for more customization of the resulting color output instead of having only a single color. |

### Power Management

(**remove this note/placeholder**: this is where your 3.3 volt switching regulator, any other needed power regulator, and power source {if applicable} **THAT WERE SELECTED**)

For more details, review the ["Appendix - Component Selection Process - Power Mangement"](https://embedded-systems-design.github.io/EGR314DataSheetTemplate/Appendix/01-Componet-Selection/Component-Selection-Process/#power-management) selection.

### Sensor

(**remove this note/placeholder**: if applicable, this is where your  **SELECTED** sensor is shown. Otherwise, remove this section.)

For more details, review the ["Appendix - Component Selection Process - Sensor"](https://embedded-systems-design.github.io/EGR314DataSheetTemplate/Appendix/01-Componet-Selection/Component-Selection-Process/#sensor) selection.

### Actuator

(**remove this note/placeholder**: if applicable, this is where your **Selected** the actuator items go, which includes both the driver and motor. Otherwise, remove this section.)

For more details, review the ["Appendix - Component Selection Process - Actuator"](https://embedded-systems-design.github.io/EGR314DataSheetTemplate/Appendix/01-Componet-Selection/Component-Selection-Process/#actuator) selection.

-----------
> Remove the following before submitting! Use them to present the selected components

### Style 1

> This is the example found in the assignment, uses more html

*Table 1: Example component selection*

**External Clock Module**

| **Component**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image1.png)<br> XC1259TR-ND surface mount crystal<br>$1/each<br>[link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)                 | \* Inexpensive[^1]<br>\* Compatible with PSoC<br>\* Meets surface mount constraint of project                                               | \* Requires external components and support circuitry for interface<br>\* Needs special PCB layout. |

**Rationale:** A clock oscillator is easier ....

### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

**Rationale:** A clock oscillator is easier ...
