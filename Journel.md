https://hackatime.hackclub.com/my/projects/z80badgev2



Day 1 Z80 Badge V2 10/8/2026

yay a new proj for gadget@hackclub :D

so yah my plan is to redesign a small badge at low cost base on the experience i gain from previous failure :|



I started to plan for ICs i need and also searched for packages for components and also planned for functions



im sorry i wrote nothing after this passage in day 1 so the other journals are some descriptions of lapse ihv recorded.



so i searched for components on Taobao and used SMD version of 62256 and 28C256.

Z80 and Z80 PIO are avail. only in DIP package so yah i dont wanna do plcc nor qfn.

so i searched and found theres a thing called SMDIP method so that we can bent dip package's legs and then solder it as a SMD component.

Aimed for lowest cost possible,i used 1602 LCD,Z80 and Z80 PIO also EEPROM and SRAM as my only main components.

I also opened 2.54 PinHeaders for Dupont wires so that i can directly write program on eeprom without using zif sockets for eeprom that is really really large.



Then i quickly choose suitable package for the ICs and try layout them in PCB design but feels not really satisfied for it so i ended today's lapse

lapses
Z80 Badge 2.0 10/8/2026 (FU5W78anlhWe)

1h 14m

Day 1 Z80 Badge 2.0 (sk8yRzNYfhxx)

45m

Total: 2hrs



Day 2 Z80 Badge V2  11/8/2026

So i redesigned the whole layout and finally get something that im satisfied with

then i started to route the whole pcb.
i started with the EEPROM and SRAM part cuz data bus and address bus are the most annoying stuff for this pcb design.
then i routed all the data bus and address bus into a single bus and used a erm Vertical-Horizontal-Dual-Layer routing (idk what thats called) so like basically u mainly use 1 layer of pcb to do 1 direction of routing.
this routing method helped reduce the difficulty while u route address and data bus that its order is not the same.



Z80 Badge 2.0 11/8/2026 (txopF1eqykIc)

1h 42m

Total: 1hr 45mins



Day 3 Z80 Badge V2 14/8/2026

yay its almost finished!
i rounded the corner of the PCB and then rerun the drc test and organized the lapses and write this journel lol.

erm yah cuz this pcb is almost full of components i dont really wanna put silkart on it but i added some text on it with my fav. font (IMPACTTTTT)

so the next step is to make a proper BOM.csv and estimate the cost needed to make 5 of it.
Then I Finished the Readme and lets upload to gadget-market-ship!
(but i hope i can make 10 of it if i can :|)
Day 3 14/8/2026 Z80BadgeV2 (lA8LdgRuLn9C)
Total: 1hr 30mins
