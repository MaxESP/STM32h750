PCB project Based on STM32H750VBT6




Finally the first debug work after soldering all the components .

Return of experience.

1 Be aware to put the small point of the mcu stm32h750 as pin 1 and not the visual one point with can be easy see without microscope.

2 I have made a mistake with the choice of crystal by buying a tristate complete resonator clock on aliexpress  in place of a basic crystal .


If you make this choice make sure to design  the tristate clock like this:

1 tristate pin  must have the option to be grounded , link to vcc or keep floating ( 3 options ).
The lack of datasheet make me wast time Solution for me witch work was keep floating.

3 The connection with the mcu is output of clock direct to osc in of the mcu.
The osc out of mcu not connected.

