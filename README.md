# OpenExoAmp
Bio-signal Amplifier

### OBJECTIVES:
<P align="justify"> The objective of this project is to develop a bio-signal amplifier for sensing physiological signals.

### DESCRIPTION:
<P align="justify"> Block diagram of an amplifier (OpenExoAmp) for bio-signal amplification and filtering. The amplifier is built with commercially-off-the-shelf components and powered by a pair of batteries. A pre-amplifier section with high common-mode-rejection-ratio (CMRR) is used to differencially pick the bio-signal. If differential input is not required, the inverting input can be shorted with the input reference terminal. The signal is then band-passed filtered and amplified to the desired value by controlling the gain of the amplifier. One can directly use this analog signal or digitised by an analog-t-digital converter (ADC) and a a microcontroller (MCU). The digitised signal can be transfered to a computer via serial network (USB). Note that many MCU boards have built-in ADC and USB interfaces that can be used for the ditisation of the amplified bio-signal. 

![Block-Diagram](https://github.com/RehabExo/OpenExoAmp/blob/main/BlockDiagram.png)

### DISCLAIMER:
<P align="justify"> The design is offered as it is. Although it has been regorously tested with utmost care and to the best of my knowledge, I do not provide any warranty in any aspect.

### WARNING:
- The design is intended stricktly for research and education purposes.
- The stimulator is not approved for human or animal use without receving prior approval from a local ethics committee such as Institutional Review Board.

### LICENSE:
##### Documentation licensed under the Creative Commons Attribution Share Alike 4.0 International License
