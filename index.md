This github page was created to facilitate the delivery of arduino package(s):
1. ```https://micooke.github.io/package_nRF5_smartwatches_index.json```

Which installs the latest release of:
1. https://github.com/micooke/arduino-nRF5-smartwatches

### Installing via Board Manager
1. [Download and install the Arduino IDE](https://www.arduino.cc/en/Main/Software) (At least v1.6.12)
2. Start the Arduino IDE
3. Go into Preferences
4. Install the board package(s)
    4.1 (If you havent already done so) Install @sandeepmistry's nRF5 core [arduino-nRF5](https://github.com/sandeepmistry/arduino-nRF5)
    4.2 Add ```https://sandeepmistry.github.io/arduino-nRF5/package_nRF5_boards_index.json``` as an "Additional Board Manager URL"
    4.3 Install [arduino-nRF5-smartwatches](https://github.com/micooke/arduino-nRF5-smartwatches)
    4.4 Add ```https://micooke.github.io/package_nRF5_smartwatches_index.json``` as an "Additional Board Manager URL"
5. Open the Boards Manager from the Tools -> Board menu and install "Nordic Semiconductor nRF5 Smartwatches"
6. Select your nRF5 smartwatch from the Tools -> Board menu

### Other Pages
[Taida Century nRF52 mini board / nRF52832 Gold Core](nRF52832_TaidaCentury_GoldCore/README)
