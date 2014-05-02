Build and Programming Instructions
----------------------------------

1.  Install WinAVR

2.  Install Arduino

3.  Open command prompt

4.  Navigate to source directory

5.  Run `make`

6.  Run `make program_serial`



Note: ensure the following makefile values match your setup, arduino install directory
and com port

`SERIAL_AVRDUDE = "C:/Program Files
(x86)/Arduino/hardware/tools/avr\bin/avrdude" `

`SERIAL_AVRDUDE_CONFIG = "C:/Program Files
(x86)/Arduino/hardware/tools/avr\etc\avrdude.conf" `

`SERIAL_AVRDUDE_PORT = COM3 `
