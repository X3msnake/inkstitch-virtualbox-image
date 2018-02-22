# inkstitch-virtualbox-image
Image compiled for Lexelby inkstitch extension for inkscape - 64Bit Debian VM image based on DietPi with gimp atom and inkscape 

[Download Latest Release > Inkstitch VM Debian 64bit](https://github.com/X3msnake/inkstitch-virtualbox-image/releases/latest)

### INSTALLATION 

#### ALL OPERATING SYSTEMS

- Unzip the image

#### WINDOWS
- Make sure your pc bios has [virtualization on](https://www.youtube.com/watch?v=f8qYmpLzo60) 
- Install [Virtualbox](https://www.virtualbox.org/)
- [Download](https://mega.nz/#F!NupgDY7a!aod3BMqECzMkJXvuXYAKkQ) image 
- Double click on the file or open VB and do [Import](https://www.maketecheasier.com/import-export-ova-files-in-virtualbox/)

#### MAC
- Install [Virtualbox](https://www.virtualbox.org/)
- [Download](https://mega.nz/#F!NupgDY7a!aod3BMqECzMkJXvuXYAKkQ) image
- Right click on image and choose run with VirtualBox

#### LINUX
- You probably don't need this VM as you can use one of the inkstitch releases for [64bit](https://github.com/lexelby/inkstitch/releases/latest) or
 [32bit](https://github.com/lexelby/inkstitch/releases/tag/dev-build-32bit)
 
#### Root User / Pass - To use with network access from the host OS or terminal ops in the Guest OS if needed
User: root
Pass: DietPi

----

### Transfering files between Guest and Host
The VM creates a network share with the name DIETPI that can be acessed using the user and pass trough the Host network map

On Windows you can directly drag files from the Guest to the host.

The image will show up in your network as DIETPI, you can also acess the shared folders and even mount them as drives for easy share between Guest and Host


### Other info
The Vm was built over [DietPi](http://dietpi.com/phpbb/viewtopic.php?f=8&t=390) VM image on VirtualBox 5.1.28

Virtual Box Guest addtitions is installed wich allows for seamless integration in windows machines

Software installed:
- Inkscape 0.92.1
- Inkstitch Extension
- Gimp 2.8.18
~~- Atom 1.23.3~~
- Firefox ESR 52.6.0

