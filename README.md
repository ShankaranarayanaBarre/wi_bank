# wi_bank
This project is used for wifi backup.
The project is initailly designed similar to micro ups. Hoever, the requirement is to design a lo cost solution.
References:
1. Micro UPS. http://www.mini-box.com/picoUPS-100-12V-DC-micro-UPS-system-battery-backup-system
2. ICL7665 : https://datasheets.maximintegrated.com/en/ds/ICL7665.pdf
3. TPS2412 : http://www.ti.com/lit/ds/symlink/tps2412.pdf

we are going to use the ICL7665 Mocro processor voltage monitor in battery backup application. 
TPS2412 N+1 and ORing poer rail controller is used to connect the two inputs to the output.

Lets start with the block diagram in schematic.
