O Raspberry Pi Pico tem oito pinos **GND** , portanto, quando você estiver usando jumpers para conecta-los, poderá conectar apenas oito componentes, a menos que alguns compartilhem o mesmo pino **GND**.

![Uma ilustração do Raspberry Pi Pico com os pinos de aterramento destacados.](images/gnd-pins.png){:width="400px"}

Os alto-falantes só podem tocar uma nota por vez, então você precisará de vários alto-falantes se quiser tocar vários sons ao mesmo tempo.

Há apenas um pino **3V** , então você só pode usar um potenciômetro. Há também um limite de quanta corrente o Raspberry Pi Pico pode fornecer.

As combinações sugeridas de entrada e saída seriam:
+ um potenciômetro e uma campainha
+ quatro botões e campainhas
+ oito botôes combinados e uma campainha
+ Um potenciômetro, dois botões e duas campainhas
+ Múltiplos botões, e um número de campainhas correspondente para reproduzir acordes (várias notas simultaneamente)

Você pode usar mais componentes do que os **8**, mas isso envolverá o compartilhamento de pinos **GND** entre eles.