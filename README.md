# WLED Strip

## Stuff you need

- [Power Supply](https://de.aliexpress.com/item/1005001303324684.html?spm=a2g0s.9042311.0.0.1af34c4dsxGvdi)
- [Dev Board](https://de.aliexpress.com/item/33005775828.html?spm=a2g0s.9042311.0.0.1af34c4dsxGvdi)
- [DC Jack](https://de.aliexpress.com/item/4001249055244.html?spm=a2g0s.9042311.0.0.1af34c4dsxGvdi)
- [WS2812B Strip](https://de.aliexpress.com/item/4000744445376.html?spm=a2g0s.9042311.0.0.1af34c4dsxGvdi)
- [Arduino Board](https://de.aliexpress.com/item/32681374223.html?spm=a2g0s.9042311.0.0.1af34c4dsxGvdi)
- [Power Switch](https://de.aliexpress.com/item/1000005699023.html?spm=a2g0o.productlist.0.0.dc7a49884fgCJc&algo_pvid=349added-03dd-465d-8b98-af15a6a31dc2&algo_expid=349added-03dd-465d-8b98-af15a6a31dc2-6&btsid=0bb0623b16032974595235601e0455&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)
- [Terminal Block](https://de.aliexpress.com/item/32993227789.html?spm=a2g0o.productlist.0.0.54e8653aAznjTx&algo_pvid=60374bb4-2752-4200-9a21-e393b7c86d24&algo_expid=60374bb4-2752-4200-9a21-e393b7c86d24-2&btsid=0bb0623616032992973188367ed634&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)
- [Wire Connector](https://de.aliexpress.com/item/4000145341391.html?spm=a2g0o.productlist.0.0.6fdc46b9sdjcnh&algo_pvid=89ddaae7-6b22-435b-ac7c-fb46ebc3fd3c&algo_expid=89ddaae7-6b22-435b-ac7c-fb46ebc3fd3c-7&btsid=0bb0623616032993704351961ed634&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_)
- [LED Profile](https://www.topled.ch/SILER-Aufbauprofil-Aluminium-eloxiert) (from a local store)
- [Software](https://github.com/Aircoookie/WLED)
- 3D Printer (I used a Alta+)

<br>
<br>

## 3D Printing
Just download the [models](/doc/3d_objects/) and you are good to go.

<br>
<br>

## Software
Download the [actual version from Aircookie's github](https://github.com/Aircoookie/WLED/releases) and flash it to the arduino board.

<br>
<br>

## Soldering
If you did order the Dev Board in the description you just can cut it in half.<br>
It should fit to the 3D print object ground.<br>
Soldering like the picture below.<br>
![](/doc/pic/pic1.jpeg)

<br>
<br>

Back: <br>
![](/doc/pic/pic2.jpeg)

<br>
<br>

Now attach the wires.<br>
![](/doc/pic/pic3.jpeg)

<br>
<br>

Back:<br>
![](/doc/pic/pic4.jpeg)

<br>
<br>

Now attach the wire connectors.<br>
![](/doc/pic/pic5.jpeg)

<br>
<br>

Fit the arduino board inside the 3D print.<br>
![](/doc/pic/pic6.jpeg)

<br>
<br>

![](/doc/pic/pic7.jpeg)

<br>
<br>

Get the top on it (maybe you should do this before connecting the wires).<br>
![](/doc/pic/pic8.jpeg)

<br>
<br>

Finished :)<br>
![](/doc/pic/pic9.jpeg)

<br>

[Video: (click on it for youtube)](https://www.youtube.com/watch?v=cf00crw5-ws):<br>
[![wled](/doc/vid/wled.gif)](https://www.youtube.com/watch?v=cf00crw5-ws)

<br>
<br>


## Home Assistant
You can use this led in Home Assistant. Just add it under integrations and it should be fully compatible with it.

<br>
<br>

## Extra
If you want to use the LED light with audio, just try [LedFX](https://github.com/ahodges9/LedFx) it works like a charm with Aircookie's Wled.<br>

<br>

[Video: (click on it for youtube)](https://www.youtube.com/watch?v=0bXIf_zYLFY):<br>
[![ledfx](/doc/vid/music.gif)](https://www.youtube.com/watch?v=0bXIf_zYLFY)
