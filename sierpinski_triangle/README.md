This folder contains two different programs for drawing the sierpinski triangle
on the fx-cp400.

##BASIC##
The first program is `sir` (sierpinski-recursive). This is a basic program.
Import it on the calc and run it with the arguments `10,10,8`.
Where 8 is the size and must be a power of 2 (eg. 1,2,4,8,16,32,64,128). 
A size of 8 will give a triangle 16 pixels wide.
The other two arguments are the position of the top left corner.

##hh##
The second program does exactly the same as the first one. The only difference
is that it is written directly in machine code (the assembly instructions are
in the comments next to the hex valuse).
This is considerably faster. It always uses a size of 128 
(256px wide on the screen that is 320 wide).
To run this program, you need hollyhock-2 installed on your calculator 
(https://github.com/SnailMath/hollyhock-2/releases).
Import the variable like you would import any other variable and place it in a folder called `hhk`. Go into the 'Menu' -> 'System' -> click in the top left on 
'System' -> click on 'Hollyhock-2 Launcher', select 'Sirpinski2' from the 
dropdown and click Run.

The hhk program was written directly on the calculator, so the messy hex file 
is the only file I have, there was never any actual source code.
(If you change something in the assembly code, make sure to change the hex on the left as well and correct every offset by hand.)

