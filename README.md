# Arduino project page

### Project description

The purpose is to move the camera on the rail in intervals. The necessary parameters are provided in the Windows application and sent to the device via ethernet.

### Equipments

- [x] Arduino Uno
- [x] A4988 Driver
- [x] Stepper motor 39BYGH 405B
- [x] Rail
- [ ] Limit switches (Missing!!!) 

### Requirements

- Start of the process possible at both ends of the rail
- Determination of...
  - interval lenght
  - interval time
  - direction
  - start position
  - start and end condition
- Pause, stop and reset process if need

I'll add some images and code during the process...

### Interface

![Interface](img/Interface.png)

#### Requirements

- All TextBoxes must be filled (zero if neccessary)
- Play and pause (toggle button)
- Stop and reset (toggle button)
- Direction change and offset
- Some info print (request response)

### Links

[WinForm app](https://github.com/temppase/UnoControlApp)

[Arduino tests](https://github.com/temppase/ArduinoUnoTest)
