Procedure:

* Generate pooyan prom files using script in tools/pooyan_unzip folder.
* Copy the pooyan_prog.vhd file into the pooyan sram_loader/prom folder.
* Compile the sram_loader project in quartus.
* Program DE2-35 Board (JTAG). The DE2 SRAM will now contain pooyan prog code.
* 7seg display and green leds can confirm correct hex and binary byte values using switches to select address.
* Without switching off DE2-35, compile the pooyan project in de2 folder and program DE2-35 (JTAG).
