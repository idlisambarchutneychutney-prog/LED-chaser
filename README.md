# LED-chaser

A custom printed circuit board designed to act as an animated backlight for a 3D-printed statue of Lord Shiva. The circuit uses a 555 timer to generate a clock pulse and a CD4017 decade counter to create a chasing LED sequence.

# Overview & Design Process
This project was designed in KiCad over the course of about 4 hours. While I used the [Hack Club Blinky Blueprint](https://blueprint.hackclub.com/starter-projects/blinky) as a foundational reference for the circuit logic, the physical board layout and form factor are entirely custom. 

# Hardware & 3D Integration
I built this specific PCB layout to serve as a custom lighting fixture for a 100mm x 100mm 3D-printed statue. The PCB dimensions were strictly constrained to remain completely hidden behind the print. 

To achieve a glowing halo effect:
* The 5mm LED footprints are routed in an inverted "U" shape along the perimeter of the board.
* The LEDs will be reverse-mounted on the back of the PCB. 
* When powered, the chasing sequence will smoothly frame the statue from behind.

# Bill of Materials (BOM)
https://docs.google.com/spreadsheets/d/1dknvj6RsMCPzlCs72U_A4Biw2XVm9xkfnfsrWRNoysQ/edit?usp=sharing

## Manufacturing
To manufacture this board, download `gerber.zip` from the root directory and upload it to a fab house like JLCPCB. The board is designed with standard 2-layer specifications and fits within a 100x100mm footprint.

## License
This project is completely open source under the MIT License.
