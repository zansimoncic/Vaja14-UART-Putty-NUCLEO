# Vaja14-UART-Putty-NUCLEO


c)  Privzeto je UART2 vmesnik povezan na USB priključek razvojne ploščice. Katere dva mostička bi morali odspajkati in kateri dve povezavi pospajkati, da bi lahko uporabili pina Tx/D1 in Rx/D0? SB62 in SB63, SB13 in SB14.

e)  V področju Connectivity aktivirajte protokol USART2 kot asinhroni. Katera dva pina sta se pobarvala zeleno oz. se aktivirala? PA2 in PA3.

f)  V polju Configuration izbranega serijskega vmesnika pustimo privzeto hitrost (Baud   Rate), ki znaša 115200 Bits/s.

d)  Za to funkcijo zapišite ukaz za vklop/izklop zelene LED (pomagajte si z metodo toggle, glej vaja0a). HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_5);_.

e)  Dodajte še ukaz za zakasnitev s funkcijo Delay iz knjižnice HAL, in sicer 2 sekunde  (glej vaja0a): HAL_Delay(1000).

Program sva dopolnila tako, da sva dodala HAL_Delay(100); v USER CODE BEGIN 3, kar nama je omogočilo izpis imen z vsakim pritiskom na tipko USER.

Komentar: Na začetku sva imela težave pri sami izbiri COM priključka, saj računalnik ni zaznal pravega. Ko sva tega zamenjala je naloga delovala brez težav.
