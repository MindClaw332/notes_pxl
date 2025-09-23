Windows -> meest populair desktop
alernatieven:
- mac
- chromeOS
- linux

linux -> desktop niet popu MAAR server/IOT (internet of things)/mobiel wel

leuke links en uitspraken (lees nog eens door van tijd tot tijd):
- [De meeste supercomputers draaien op Linux](https://www.top500.org/statistics/details/osfam/1/)
- [111+ Linux statistieken en feiten – Linux Rocks!](https://webtribunal.net/blog/linux-statistics/)
- [De populairste cloudinfrastructuurproviders gebruiken Linux](https://www.linuxfoundation.org/blog/how-amazon-web-services-uses-linux-and-open-source/)

## linux
eerst en vooral een OS gemaakt door Linus Torvalds
naam voor alles met linux kernel (distro's)
uitgekomen: ==17 september 1991== 
android is gebaseerd op linux kernel
desktop ook veel populairder onder devs
linux mascotte -> tux

voordelen:
- veiliger
- snellere filesystem
- open-source en meestal gratis

most used linux tools:
- **[Rsync](https://rsync.samba.org/) – open-source backup tool.**
- [Dropbox](https://www.dropbox.com/?landing=dbv2) – cloud storage.
- [Google Drive](https://www.google.com/drive/)….more storage.
- [Aria2](https://aria2.github.io/) – download manager.
- [Thunderbird](https://www.thunderbird.net/en-GB/) – email platform.
- [GnuCash](https://www.gnucash.org/) – finance software.

## unix
uitgevonden door: ==Dennis Ritchie en Ken Thompson== in 1969 (was open source)
Bell labs wou het verkopen/ BSD bleef devven
- Unix: De commerciële versie
	- HP UX
	- solaris
- BSD Unix: De open source versie (BSD: berkely software distribution)
	- ultrix
broncode werd herschreven -> GNU project ("GNU is not unix") -> had geen kernel

Linus in jaren '90 eigen besturingssysteem

snelle tijdlijn:
- research UNIX 1969
- commercial UNIX 1982
- GNU 1983
- Minix 1986
- uit gnu en minix onstaat linux 1991
- eerste distros (debian en slackware) 1993
- 2001 macOS
- 2005 GIT gemaakt door linus
- 2013 GIT word populairste versie controle

## distro's
distros zijn opinianated versie van linux 
de kernel is hetzelfde maar alles er rond is anders
soms bedoeld als specifieke usage
vereenvoudigen ook de installatie
voorbeelden:
- arch
- debian
- ubuntu
- manjaro 
- mint
- redhat
![distros](https://vwgert.github.io/be-nl/images/01/distros.png)

## unix vs linux
multix -> gemaakt om meerder programmas tegelijk te runnen -> thomas en ritchie vonden het slecht begonnen aan unics (uniplexed information and computing service) -> werd UNIX

OS werd uiteindelijk herschreven in C -> mochten het niet echt uibrengen dus licensed source code -> uiteindelijk commercieel System V

beiden nog steeds onder zelfde license dus herschreven BSD het
lawsuit -> BSD 4.5 lite
er is nu een filosofie rond UNIX -> elk programma doet iets specifiek/compatibility

Tegelijkertijd -> GNU foundation -> richard stallman (Free software)
ook GNU c compiler etc
Minix -> andrew tannenbaum -> teaching tool
linus herschrijft problemen in minix -> zelfde filosofie als UNIX
linux werd populair in 1992 -> toen WM geport werd

linux is eigenlijk een clone van UNIX ook al gebruikt het de source code niet -> zelfde filos
er zijn binnen de dev tree zelfs nog references naar UNIX

## wat is linux?
several pieces:
- bootloader -> software die het booten van de pc managed
- kernel -> effectief linux -> de kern managed de CPU het geheugen en peripherals(muis bijv)
- Init system -> een subsysteem dat user-space bootstrapt en daemons controleert meest gebruikt is systemd -> managed booten na de bootloader
- Daemons -> background service zoals printen of geluid
- graphical server -> subsysteem dat graphics laat zien
- desktop environment -> het stuk waar effectief mee geinterageerd word
- applications -> externe apps

### waarom gebruiken?
- perfect customisable
- gratis
- open-source
- veiliger
- stabieler

open-source heeft deze kenmerken:
- de vrijheid om het programma te runnen
- de vrijheid om het programma te bestuderen en aan te passen
- de vrijheid om kopies uit te delen om zo iemand te helpen
- de vrijheid om je aangepaste versie uit te delen aan anderen
cruciaal om de cultuur rond linux te begrijpen

nadelen:
- minder ondersteund bijv games
- hogere skill floor (terminal leren is het best)


