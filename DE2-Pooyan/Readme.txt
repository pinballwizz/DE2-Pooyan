Pooyan Arcade for the Altera DE2-35 Dev Board.

Notes:
Controls are PS2 keyboard, see readme file in de2 folder for instructions.
Use the included SRAM loader project to load Pooyan program prom code to DE2 SRAM.

Build:
* Obtain correct roms file for Pooyan, see make_pooyan_proms script in tools/pooyan_unzip folder for rom filenames.
* Unzip rom files to tools/pooyan_unzip folder.
* Run the make_pooyan_proms script in the tools/pooyan_unzip folder.
* Place generated prom files into proms folder (except the pooyan_prog.vhd prom file - see below)
* Place the pooyan_prog.vhd prom file inside the pooyan sram_loader/proms folder (see readme file inside the folder).
* Compile and program the pooyan sram loader project into DE2-35. (see readme file in sram loader folder).
* Open the pooyan_de2 project file using Quartus and compile.
* Program DE2-35 Board.
