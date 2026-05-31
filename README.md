# Benchtop-Power-Supply
This project consists of a custom made power supply that can be used for testing electronics. I decided to make my own power supply in order to have a hands-on project to practice basic engineering skills. Some skills I developed/worked on is design/layout of a project, power electronics, wiring/soldering, as well as PCB/Schematic design. 

I used this page as my main reference when working on this project: https://www.instructables.com/Build-your-own-Variable-Lab-Bench-Power-Supply/

I based my choice of materials, wiring methods, and the general project on this reference. My build uses some different parts so I had to make some changes in order to make it work properly. I will have a bill of materials showing the materials used as well as the cost.

In order to differentiate my build further, I decided to create my own circuit board. The enclosure I bought didn't include vents or a cooling method. I decided to make my circuit board use a small motor fan along with some small vent holes drilled into the lid in order to have cooling for my project. I used Kicad to draw my schematic and pcb. I protoyped the circuit using a breadboard and arduino. The board is mounted to the lid and will spin and cool the enclosure while it runs. More documentation will be provided in the folder.

A general overview of my project:

I did my main power wiring with 14 awg copper speaker wire, the signal connections and banana plug connections used 18 awg speaker wire. The potentiometer used 22 awg jumper wires. The power supply outputs 12v, 5A, and 60W. The power convertor board has the potentiometer connections, and the left side connects to the power supply with positive and negative voltage connections. The right side has the positive side connect to the red banana plug and the negative connects to the shunt and volt/current display. The black banana plug connects to the shunt. The shunt also has all of the connections for the volt/current display. The power outlet has power connections to the bottom of the switch and the top of the switch connects to the power supply. The switch connects to the line and neutral connections on the power supply. I have four wires for the ground, one wire is from the outlet, another goes to the power supply, and each side has a ground screw on the outside of the enclosure. Most of my connections were made with ring and slide terminals. 

If I did something like this again, I'd probably do a few things differently. One of the biggest things I'd change is the wiring colors. I only had blue 14 awg copper speaker wire so I'd buy at least 2-3 colors so wiring would be easier. I used a dremel to cut the holes for the switch, outlet, and volt/current display. These holes werent as neat as I wanted them to be. So if I did this project again, Id more closely plan out the layout of the project/design and more carefully execute the cuts. 

Some other references:
https://github.com/kitspace/awesome-electronics
https://www.switchelectronics.co.uk/blogs/news/led-polarity-basic-guide
I used Chatgpt for a few questions as well. 
