# Z-Turn-IO-Board
my own expansion board which converts the 1.27mm pitch connector to 2.54mm pitch connector for Z-turn board (http://www.myirtech.com/list.asp?id=502) from MYiR

###
A lot of design is borrowed from the IO Cape board (http://www.myirtech.com/list.asp?id=532) of MYiR, where I converts the Connector 1 to 6 PMOD compatible (2.54 mm dual row 12 pin header) headers and 1 40 pin FFC/FPC connector (for LCD); and Connector 2 to 2 PMOD headers plus 2 2.54mm dual row 34 pin header. Especially:

CN1, CN2, two 1.27mm pitch dual row 80 pin headers from Z-turn board;
J1,J2, two 2.54mm pitch dual row 34 pin headers for FPGA differential pin (12 pairs each);
LCD, 40 pin FFC/FPC connector;
MISC, PMOD header for I2C;
I2S, PMOD header for I2S and HDMI;
J3, J4, J5, J6, PMOD header for FPGA differential pin (4 pairs each);
ADC, PMOD header for XADC input (two pairs of analog input);
MIO, PMOD header for ARM IO pin (8 pins);
Note, the differential pins is not ready for high speed differential usage yet, as the length is not properly configured.
