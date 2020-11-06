NALOGE NISEM USPEL NAREDITI SAJ NISEM IMEL OSCILOSKOPA. NAREDIL SEM KOLIKOR SEM LAHKO KODE MI NOCE GENERIRATI SAJ JAVLJA NAPAKO KO SEM KONFIGURIRAL IN  VSE NASTAVLJAL.MISLIM DA JE TEZAVA V TEM KER SEM DAL STM32F40C-DISCO MORAL PA BI BITI STM32F4OC-DISCOVERY, KI GA PA NISEM NAŠEL OZIROMA SPLOH GA NI BILO PRI MENI NA RAČUNALNIKU.ČASA SEM IMEL DOVOL A TEŽAVE NISEM ZANAL REŠITI ALI PA JO POPRAVITI.




b)	V levem Pinout oknu razširite nabor možnosti za Timers ter za časovnik TIM1. Clock Source nastavite kot Internal Clock. Prvi kanal aktivirajte kot PWM Generation CH1. Kateri pin ste omogočili?PE9.
Kaj se izpiše poleg pina?TIM1_CH1.

d)	V Oknu Configuration kliknemo za TIM1  Vrednost Prescaler v zavihku Counter Settinngs določite tako, da bo časovnik delal s frekvenco 1 MHz. Koliko je vrednost Perscaler (namig; delitelj) ?16.

e)	Parameter Counter Period nastavimo na 100 in s tem še dodatno znižamo takt časovnika. Koliko znaša sedaj? 10kHz.
