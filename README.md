# Vaja-3--ADC-conversion-with-time-interrupts


b) V Analog razdelku levo od sheme mikroprocesorja kliknite Analog. Koliko je vseh ADC pretvornikov?

Trije pretvorniki

c) Izberite ADC pretvornik in v njem izberite (prosti) kanal, kjer boste zajemali analogno (single-ended) 
meritev. V oknu Pinout View se določen pin pobarva v zeleno – dopolnite:

Naslov dodeljenega pina: IN4 Single-Ended
Ime izbranega kanala: PC3
Oznaka (label) ob dodeljenem pinu: ADC3_IN4

f) Uporabili bomo samo zeleno LED diodo, ki je na izhodu/pin-u PA5.


g) V Clock Configuration spremenimo APB1 Timer clocks (MHz) na 16 MHz (pritisnemo ENTER). Kaj opazite?

Ostale vrednosti se tudi spremenijo, npr. ABP1 peripheral clocks se spremeni na 8MHz


j) V razdelku TIM2, pod Timers, bi radi časovniku spremenili frekvenco na 1 kHz, zato moramo prej določeno 
frekvenco ABP1 Timer Clock preskalirati v polju Prescaler (PSC – 16 bit value). Koliko znaša ta vrednost? 
16MHz. Vpišite to vrednost v zahtevano polje

