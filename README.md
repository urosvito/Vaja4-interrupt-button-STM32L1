# Vaja4-interrupt-button-STM32L1

KOMENTAR NA DELOVANJE :

Naprava deluje brezhibno in nama ni delala nikakršnih težav.

ODGOVORJI NA VPRAŠANJA:

2b) pin PA0

2C) zelena PC9
    modra  PC8
    
PROGRAMIRANJE:

c) HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9);

d) 9999 milisekunde

e)HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_8);

f)HAL_Delay(500);

a) Z modro LED se nič ne zgodi.
