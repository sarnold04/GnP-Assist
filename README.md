<h1 align="center">GnP Assist</h1>

![GnP Assist](Images/GnP_assist.png)

## Description
GnP assist is inspired by the PnP-Assist project of
Nuri Erginer(https://github.com/makerstorage)

The intention of this project is to assist during the PCB assembly(especially
SMD parts) process and to reduce the amount of errors during this process.

The processor unit houses a Raspberry PI, the GnP Raspberry PI HAT, power supply
and a 7" touch display. After the gerber and part placement files have been
loaded, the systems shows each part which needs to be placed on its specific
location, moves/rotates the mounting tray so that the position of the part on
the PCB is in the center of the tray and highlighted by the laser cross.

The system also has an inventory system which holds up to 50 parts in the tray
of the main unit. The tray rotates the part, which should be placed,
to the front, so that it's directly in front of the operator.
With the additional GnP assist addon board, which will be connected via USB,
it's possible to extend the storage space with parts on tape.
If needed during the assembly the tape with the part in question gets
highlighted with a small LED besides the tape.

## License
GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007 See `LICENSE`
for more information.

## Contributing
Bug reports and pull requests are welcome on GitHub at
https://github.com/sarnold04/GnP-Assist.
