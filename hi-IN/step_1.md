The Raspberry Pi Pico has eight **GND** pins so when you are using jumper wires, you can only have eight components unless some share a **GND** pin.

![An illustration of the Raspberry Pi Pico with the ground pins highlighted.](images/gnd-pins.png){:width="400px"}

Speakers can only play one note at a time so you will need multiple speakers if you want to play multiple sounds at the same time.

यहाँ केवल एक **3V** पिन है ताकि आप केवल एक ही potiometer का उपयोग कर सकें। There is also a limit to how much current the Raspberry Pi Pico can supply.

इनपुट और आउटपुट के सुझाए गए संयोजन हैं:
+ 1 potentometer और 1 बज़र
+ 4 बटन और बज़र
+ 8 crafted बटन और एक बज़र
+ 1 potentiometer, 2 buttons and two buzzers
+ कई बटन और कॉर्ड्स चलाने के लिए बज़र की एक मिलती-जुलती संख्या (एक ही समय में कई नोट्स)

You **can** use more components than **8** but this will involve sharing a **GND** pin.