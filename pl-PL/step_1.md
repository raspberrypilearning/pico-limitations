Raspberry Pi Pico ma osiem pinów **GND**, więc kiedy używasz przewodów połączeniowych, możesz podłączyć tylko osiem elementów, chyba że niektóre mają wspólny pin **GND**.

![Ilustracja Raspberry Pi Pico z zaznaczonymi pinami uziemienia.](images/gnd-pins.png){:width="400px"}

Głośniki mogą odtwarzać tylko jedną nutę naraz, więc będziesz potrzebować wielu głośników, jeśli chcesz odtwarzać wiele dźwięków jednocześnie.

Jest tylko jeden pin **3V**, więc możesz użyć tylko jednego potencjometru. Istnieje również ograniczenie prądu, jakie może dostarczyć Raspberry Pi Pico.

Sugerowane kombinacje wejść i wyjść to:
+ 1 potencjometr i 1 brzęczyk
+ 4 przyciski i brzęczyk
+ 8 niestandardowych przycisków i brzęczyk
+ 1 potencjometr, 2 przyciski i 2 brzęczyki
+ Wiele przycisków i odpowiednia liczba brzęczyków do odtwarzania akordów (wiele nut w tym samym czasie)

**Możesz** użyć więcej komponentów niż **8**, ale będzie to wymagało współdzielenia pinu **GND**.