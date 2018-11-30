# Vaja7-PWM-STM32F0
Uporaba duty cycla
.........................................................................
ODGOVORI:
2.)
b.) PA8; TIM1_CH1.
d.) 16 bit.
e.) 10KHz.
f.) Duty cycle ima 50% vrednost.

3.)
b.) sConfigOC.Pulse = 50;

4.)
c) sConfigOC.Pulse = 25;
d.)
1. Prisiljena nastavitev duty cycla z registrom.
2.  Poveča duty cycle za 10%.
3.) Ko duty cycle preseže 90% se vrne nazaj na 10%.
...........................................................................
KOMENTAR:
Na osciloskopu se prikaže najprej s prvim ukazom pokaže 50% PWM signal, ki miruje, z drugim ukazom pa se prikaže 25%, ki miruje. V končanem programu pa se duty cycle spreminja (signal več ne miruje). Ob začetku duty cycla je bilo na osciloskopu popačenje.
