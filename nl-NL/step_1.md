De Raspberry Pi Pico heeft acht **GND** -pinnen, dus als je jumperdraden gebruikt, kun je slechts acht componenten hebben, tenzij sommige een **GND** pin delen.

![An illustration of the Raspberry Pi Pico with the ground pins highlighted.](images/gnd-pins.png){:width="400px"}

Luidsprekers kunnen slechts één noot tegelijk spelen, dus je hebt meerdere luidsprekers nodig als je meerdere geluiden tegelijkertijd wilt spelen.

Er is slechts één **3V** pin, dus je kunt slechts één potentiometer gebruiken. Er is ook een limiet aan hoeveel stroom de Raspberry Pi Pico kan leveren.

Suggested combinations of input and outputs are:
+ 1 potentiometer and 1 buzzer
+ 4 buttons and buzzer
+ 8 crafted buttons and a buzzer
+ 1 potentiometer, 2 buttons and two buzzers
+ Multiple buttons and a matching number of buzzers to play chords (multiple notes at the same time)

Je **kunt** meer dan **8** componenten gebruiken, maar dan moet je een **GND** pin delen.