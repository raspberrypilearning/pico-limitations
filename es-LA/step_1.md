El Raspberry Pi Pico tiene ocho pines **GND** , por lo que cuando se usan cables de puente, solo puede tener ocho componentes, a menos que algunos compartan un pin **GND**.

![Una ilustración de Raspberry Pi Pico con los pines de tierra resaltados.](images/gnd-pins.png){:width="400px"}

Los altavoces solo pueden reproducir una nota a la vez, por lo que necesitará varios altavoces si desea reproducir varios sonidos al mismo tiempo.

Solo hay un pin **3V**, por lo que solo se puede usar un potenciómetro. También hay un límite en la cantidad de corriente que el Raspberry Pi Pico puede suministrar.

Las combinaciones sugeridas de entradas y salidas son:
+ 1 potenciómetro y 1 zumbador
+ 4 botones y un zumbador
+ 8 botones fabricados y un zumbador
+ 1 potenciómetro, 2 botones y dos zumbadores
+ Múltiples botones y un número correspondiente de zumbadores para tocar acordes (múltiples notas al mismo tiempo)

Se **pueden** usar más de **8** componentes pero esto implicará compartir un pin **GND**.