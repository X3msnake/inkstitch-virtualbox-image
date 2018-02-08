# inkstitch-virtualbox-image
Image compiled for Lexelby inkstitch extension for inkscape - 64Bit Debian VM image based on DietPi with gimp atom and inkscape 

[Download > Inkstitch VM Debian 64bit](https://mega.nz/#F!NupgDY7a!aod3BMqECzMkJXvuXYAKkQ)

### INSTALLATION 

#### WINDOWS
- Make sure your pc bios has [virtualization on](https://www.youtube.com/watch?v=f8qYmpLzo60) 
- Install [Virtualbox](https://www.virtualbox.org/)
- [Download](https://mega.nz/#F!NupgDY7a!aod3BMqECzMkJXvuXYAKkQ) image 
- Double click on the file or open VB and do [Import](https://www.maketecheasier.com/import-export-ova-files-in-virtualbox/)

#### MAC
- Install [Virtualbox](https://www.virtualbox.org/)
- [Download](https://mega.nz/#F!NupgDY7a!aod3BMqECzMkJXvuXYAKkQ) image
- Right click on image and choose run with VirtualBox

#### Root User / Pass
User: root
Pass: DietPi

----

### Transfering files between Guest and Host
The VM creates a network share with the name DIETPI that can be acessed using the user and pass trough the Host network map

On Windows you can directly drag files from the Guest to the host.


### Other info
The Vm was built over [DietPi](http://dietpi.com/phpbb/viewtopic.php?f=8&t=390) VM image on VirtualBox 5.1.28

Virtual Box Guest addtitions is installed wich allows for seamless integration in windows machines

Software installed:
- Inkscape 0.92.1
- Inkstitch Extension
- Gimp 2.8.18
- Atom 1.23.3
- Firefox ESR 52.6.0

