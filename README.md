# ElectroniqueCdF2024
Repository containing Printed Circuit Board Designs along with documentation related to the Electronics architecture of the 2024 Robot

# Electronics Architecture 
Our robot's entire electronics architecture is contained within the following folder :

# Printed Circuit Boards
Printed circuit boards files are contained within the following folder : 

When you add a printed circuit board design, you must :  

-Provide the entire KiCad project  

-Give your project a descriptive name and provide a README file  

-Make sure you have added an identifier to your PCB design's silk screen, this identifier should be constructed according to the following rules :  

<NameOfPCB>_<JJ/MM/AA>_<Vnum1.num2>
NameOfPCB should provide a succinct understanding of the board's primary purpose.
JJ/MM/AA is the date the printed circuit board design was finished.
num1 and num2 are numbers that starts at 0, num1 should increase from 0 to 1 when the board is no longer considered a prototype ( 0 = prototype). Successive increments of num1 by 1 suggest the board architecture has undergone a major reworking. Incrementing num2 by 1 signals that the board has undergone a minor change compared to the previous version.  

-Make sure you indicate your name on your design, and the name of the manufacturer (for example, JLCPCB).


