 # Micro:bit pouzdro na "Postřehovou hru" pro MBT0008

<p align="center">
   <img src="./images/Header.jpg" width="600" height="auto">
</p>

## Postřehová hra
### Jak tato hra funguje?
Hra pro dva hráče. Herní engine po náhodně dlouhé době (3–10 s) od restartu hry zobrazí "ikonu" na ledkách a zároveň (bez prodlevy) spustí tón o délce 1,5 s. Tak je indikováno zahájení hry. Úkolem hráče je stisknout "tlačítko" dříve než soupeř. "Tlačítko" lze stisknout ihned po rozsvícení led diod, ještě v době, kdy zvuk tónu zní.
Pokud je hra zahájena, herní engine po stisku "tlačítka" zobrazí výsledek hry. Existuje 6 možných výsledků:
### Výsledky
- Rychlejší byl hráč 1 → potom display zobrazí "1"	
- Rychlejší byl hráč 2 → potom display zobrazí "2"
- Oba stiskli "tlačítko" ve stejném okamžiku (v rámci reakční doby počítače) → potom display zobrazí "R"emíza
- Hráč 1 stiskl "tlačítko" jednou nebo vícekrát ještě před zahájením hry → potom display zobrazí "B"
- Hráč 2 stiskl "tlačítko" jednou nebo vícekrát ještě před zahájením hry → potom display zobrazí "A"
- Oba hráči stiskli "tlačítko" jednou nebo vícekrát ještě před zahájením hry → potom display zobrazí "C"heater
  [Code here](https://github.com/pslib-cz/2022-p2a-mme-pppp-Lukypop/blob/main/pxt-reaction-game-as-txt.txt)
  
## Tips & Tricks

- [Installing heat nuts](https://markforged.com/resources/blog/heat-set-inserts)
- [Cable crimping](https://ratrig.dozuki.com/Guide/11.+Cable+Crimping/80)
- [Soldering](https://www.makerspaces.com/how-to-solder/)

## What do you need?

- Microbit extension [MBT0008](https://www.dfrobot.com/product-1867.html)
- 2 pieces of [Insert Nut M3](https://www.aliexpress.com/item/1005004701945081.html)
- 2 pieces of [IR sensor](https://www.aliexpress.com/item/1297063929.html)
- 1 piece of [Batery Holder AA](https://www.aliexpress.com/item/1005002927831106.html)
- 1 piece of [Vertical micro USB ](https://www.aliexpress.com/item/1005002650191316.html)
- 1 piece of [Micro USB connector](https://www.aliexpress.com/item/32267930530.html)
- ~150 grams of filament ABS
- 1× 2-way cable
- 2× 3-way crimped cables
- 2× LEGO part 2780 [example](https://www.amazon.co.uk/Technic-Friction-Ridges-Lengthwise-Center/dp/B01N6WURXK/)

## Embedding parts
### Step 1:
- download and print [parts](https://github.com/pslib-cz/2022-p2a-mme-pppp-Lukypop/tree/main/parts) or [parts as STL](https://github.com/pslib-cz/2022-p2a-mme-pppp-Lukypop/tree/main/parts/STL) using a 3d printer
### Step 2:
- insert heat nuts on both sides
  
   <img src="./images/InsertNuts.png" width="350" height="auto">

### Step 3:
- insert lego parts into the holes
- place Microbit MBT0008 on these parts
  
   <img src="./images/LegoHoles.png" width="350" height="auto">
   <img src="./images/LegoHolesMicrobit.png" width="350" height="auto">

### Step 4:
- Connect IR sensor to 3-way crimped cable and put it through hole
- Screw the M3 bolt to hold IR sensor into heat insert nut

   <img src="./images/IR_sensor.png" width="350" height="auto">
   <img src="./images/IR_sensor_installed.png" width="350" height="auto">
 
- Slide sensor lids into thin holes
- Do it on both sides

   <img src="./images/IR_sensor_closed.png" width="350" height="auto">
  
- Connect 3-way crimped cables to MBT0008 on pins: 1, 2 (see image)

   <img src="./images/Extension_wired.png" width="350" height="auto">
   <img src="./images/IR_sensor_cables.png" width="350" height="auto">

### Step 5:
- put battery holder cable through hole
- connect it into MBT0008 (into [JST-PH plug](./images/JST_plug.jpg))
- place battery holder in storage place

   <img src="./images/Battery_cables.png" width="350" height="auto">
   
### Step 6:
- Connect 2-way cable with vertical micro USB plug and micro USB connector using soldering
- Be careful about + and - (see image if you are not sure)

   <img src="./images/Power_cable.png" width="350" height="auto">

- Connect micro USB into MBT0008 and glue vertical micro USB plug into pre-made hole

     <img src="./images/Power_cable_plug.png" width="350" height="auto">
     
- Close both storage places with lids

     <img src="./images/Everything_closed.png" width="350" height="auto">
     
### Step 7:
- upload the code to the micro:bit [code here](https://github.com/pslib-cz/2022-p2a-mme-pppp-Lukypop/blob/main/microbit-pxt-reaction-game.hex) or [as .txt here](https://github.com/pslib-cz/2022-p2a-mme-pppp-Lukypop/blob/main/pxt-reaction-game-as-txt.txt)
- you can use [Micro:bit MakeCode](https://makecode.microbit.org/) to download it into micro:bit easily


