## Deciding keyboard - Aug 12 - 17:48
Alrit so i guess i wanna build an alice type 60% tactile keyboard. though i have never used bt ig i would go with it..

## Planning and Layout of the keyboard - Aug 12 - 18:32 (took 2h 28m)
It was ig ez and most creative part as i had to do the main thing: Sketching and making layout for the keyboard.
At first i was skatching in krita and was googling abt abt custom alice keyboard and got this repo: https://github.com/floookay/adelheid, and soon realized we can generate layout, so i forked the layout of this repo and started making it my own. sm major changes i did was removing f1-f12 as a result changing position of many corresponding keys and after sm minor changes and wasting 2 hrs, and taking feedback from ppl and ai, i got this:
![my keeb layout](./imgs/keeb_layout.png)

## Schematics and pcb designing - Aug 13 - 6:46 (took )
Attempt 1: i knew nothing abt schematics so after reading the guide i began by installing the plugins in kicad then spent sm time struggling to create project and go to schematics tab. once it was done i began adding all components and joined diode and key switch then imported the keyboard layout as referance and duplicated the diode and switch. then as it was said i started connecting them with rows and colums wire and i was halfway but realized sm of the ends of the switch was too much close or nearly got connected to the column wire so i js deleted the project and started new.
Attempt 2: So i saw other's schematics and found out that instead of keeping it in the alice shape, they did rectangular and then got to know its js to show connection regardless of position then after sm time i finished doing this(duplicating switch/diode) then as told in guide, i labeled rows and cols and attached it with pins and heres the img: 
![](./imgs/keeb_kayboard_schemetics_part1.png)

