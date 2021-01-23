# Vaja-1-enkratna-ADC-pretvorba-z-Nucleo-L476RG
2.
b) Zelena LED je priključena na PA5 pin, modre LED ni. Kaj je pa priključeno na pin PA0? potenciometer
c) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? PA0
d) V Analog razdelku levo od sheme mikroprocesorja ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? 3 
e.1) Izbrani ADC pretvornik ima oznako s trikotnikom. Kaj to pomeni? To pomeni, da so pini, ki jih uporablja ADC pretvornik zasedeni.
e.2) Kaj morate storiti, da razrešite to omejitev? Potrebno je resetirati nekatere pine, postaviti v resetirano stanje (Zeleno LED na primer).
f) Koliko je vseh vhodnih kanalov (seštejte oznake INxx)? 15 oziroma 16, če štejemo zraven še 16. kanal, ki je zmožen samo single-ended pretvorbe. 
g) Kaj se izpiše poleg pina? ADC1_IN5
i)	Preglejte, kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti?
  a.	12-bitna ločljivost, od 0 do 4095,
  b.	10-bitna ločljivost, od 0 do 1023,
  c.	6-bitna ločljivost, od 0 do 63.

komentar:
Namesto STM32F0 Discovery sem imel NUCLEO L476RG ploščico. Zato so odgovori na nekatera vprašanja drugačni od pričakovanih. Na primer vprašanje je bilo o modri LED, a jo ploščica, ki sem jo uporabil sploh nima.
