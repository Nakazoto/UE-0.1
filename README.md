# UE-0.1
This is a small repository for the files related to the handheld tube computer. For more information, check out the video at the link below.

[Ooh, ooh, ooh, click me! Click me!](https://youtu.be/s7nx-pMQ6tM)

All files are included above, including logic diagrams, PCB design files, gerbers, and block diagram files.

![](https://github.com/Nakazoto/UE-0.1/blob/main/IMG_3282.JPG)

![](https://github.com/Nakazoto/UE-0.1/blob/main/Gates_v2.png)

## Bill of Materials

| Part | Part Number | Qty. | Notes | 
| ------------- | ------------- | ------------- | ------------- |
| Push button | KM2-1 | 1 | Different button can be used, but PCB footprint must be updated |
| Toggle switch | MT-1 | 4 | Different switch can be used, but PCB footprint must be updated |
| Tube Socket | GD-PARTS B7G | 24 |  |
| Vacuum Tube | 6AU6 | 24 | Other tubes may work, such as 6CB6, but not guaranteed |
| VFD | IV-26| 1 | COther VFDs may work, but footprint and resistor values will need to be adjusted |
| Resistor | 100 | 26 |  |
| | 330 (5W) | 1 | 3W will be fine, but I like overkill |
| | 1k | 2 |  |
| | 33k | 22 |  |
| | 47k | 7 | These are the 7 resistors for the VFD |
| | 220k | 53 |  |
| | 1M | 4 |  |
| Schottky Diode | SD103 | 37 | Any diode with more than 30V reverse protection will work |
| Capacitor | 102 / 1nF | 1	| Larger capacitor size will provide better debouncing at expense of speed |
| Pin Header | 90-degree male | 2 | Any type of header to fit your needs can be used here |
