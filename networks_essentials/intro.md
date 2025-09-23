## termen

| term                 | betekenis                                                                                                                                                                |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| cloud                | computers in de lucht waar vaak bestanden op opgeslagen worden                                                                                                           |
| network              | met mekaar verbonden apparaten                                                                                                                                           |
| internet             | het wilde westen van deze apparaten/ apparaten waar je gewoon mee kan verbinden                                                                                          |
| host                 | alles wat direct in netwerk communicatie meedoet en een nummer krijgen                                                                                                   |
| IP                   | internet protocol adress -> dit identificeert de host en het netwerk waaraan het zit                                                                                     |
| server               | een computer met software die je informatie verschaft meestal met een specifieke functie                                                                                 |
| client               | een computer met software om deze informatie op te vragen en te verwerken (er kunnen meerdere client softwares runnen op 1 computer)                                     |
| peer-to-peer network | een netwerk waar elke computer gelijk staat oftewel zowel een server als client is<br>bijvoorbeeld een computer aan een printer die van een andere computer files krijgt |
| network media        | de fysieke aparatuur waar data over beweegt                                                                                                                              |
| intermediary device  | een device dat netwerk pakketten regelt                                                                                                                                  |
| end device           | waar een signaal begint of eindigt                                                                                                                                       |
| topology diagram     | diagram van hoe het netwerk eruitziet                                                                                                                                    |
|                      |                                                                                                                                                                          |
## components
netwerken bestaan uit enkele componenten:
- hosts
- clients
- servers
### end-devices
dit zijn diegene wat we het best kennen 
ze hebben allemaal een adress het is oftewel de bron van informatie of de ontvanger en is waar het dus stopt of begint
telefoons, pcs of gsms bijv

### intermediary devices
dit verbindt alle end devices met mekaar dus routers switches of firewalls

kunnen ook netwerken verbinden om zo een internetwerk te maken. ze zorgen voor verbundingen en het vloeien van info doorheen het netwerk

functies:
- het regenereren en heruitzenden van signalen
- behouden van informatie over de paden door het netwerk en internetwerk
- andere apparaten duidelijk maken als er iets niet werkt
- data leiden door alternatieve paden wanneer er iets fout is
- classificeren en doorlaten van data op basis van prioriteit
- het toestaan en afslaan van informatie op basis van beveiliging

### network media
data beweegt dmv media dit zijn hier de kanalen voor

voornamelijk drie soorten:
- metaal in kabels (meestal koper) -> data is gecodeerd naar electriciteit
- fiber-optics: data ivv licht
- wireless: data ivv frequenties en electromagnetische golven
vier criteria voor keuzes:
- maximum lengte van transmissie
- omgeving waar we het gebruiken
- hoeveel en hoe snel data
- hoeveel kost het
### peer-to-peer

| voordelen                             | nadelen                                                                   |
| ------------------------------------- | ------------------------------------------------------------------------- |
| makkelijk op te zetten                | geen gecentralizeerde admin                                               |
| minder ingewikkeld                    | niet zo secure                                                            |
| vaak goedkoper                        | niet schaalbaar                                                           |
| goed voor simpele taken zoals printen | aangezien alles als zowel server als client kan werken is het vaak trager |
|                                       |                                                                           |
## representaties en topologie
als netwerk architect moet je natuurlijk kunnen laten zien hoe alles eruitziet dan maken we diagrammen -> topology diagram

bovenop de visuele representaties is er ook terminolgie om te bescchrijjven hoe deze apparaten verbinden:
- NIC -> network interface card -> fysieke verbinding aan het netwerk
- physical port -> een connector of outlet op een netwerk device 
- interface -> gespecialiseerde poorten om een netwerk apparaat te doen verbinden met individuele netwerken

### physical topology diagrams
dit laat de fysieke locatie van alle network devices zien bijvoorbeel rack1 shelf 1
![[Pasted image 20250923145622.png]]

### logical topology diagrams
deze laten de poorten en adressing schemas zien maar ook welke media er word gebruikt
![[Pasted image 20250923145717.png]]
## types of networks

- small home network -> een paar computers naar mekaar verbinden en naar het internet
- SOHO netwerk -> small office and home office -> verbind met bedrijfsnetwerk of geraak en centrale resources
- medium to large -> school en bedrijven met honderden apparaten
- worldwide -> het internet
### LAN vs WAN
LAN -> local area network -> klein gebied -> meestal thuis of klein bedrijf
WAN -> wide area network -> een groot gebied -> meestal gemanaged door een isp

LAN:
- interconnected in klein gebied
- meestal admin kleine organisatie of persoon op netwerk level
- hoge snelheden tussen end devices en intermediary

WAN:
- verbind LANs over groot gebied
- meestal admin meerder service providers
- trager dan LAN

### het internet
een wereldwijde collectie van ondermekaar verbonden netwerken -> LAN verbonden door WAN en dan verbonden met mekaar

er zijn standaard protocollen en processen gemaakt door organisaties:
- IETF -> internet engineering task force
- ICANN -> internet corporation for assigned names and numbers
- IAB -> internet architecture board

### intranet en extranet
intranet zijn LANs en WANs met mekaar verbonden binnen een dezelfde organisatie -> enkel beschikbaar voor mensen binnn die organisatie

extranet -> om mensen van buiten de organisatie gelimiteerde access te geven tot intranet
![[Pasted image 20250923151317.png]]
## hoe verbinden?

### home en office internet
- cable: via dezelfde kabel dat tv binnen brengt meestal reliable en always on
- DSL -> digital subscriber lines -> gaat over de telefoon lijn meestal een assymetric DSL wat betekent dat download sneller is dan upload
- cellular -> over de cellphone netwerken
- satellite -> goed voor plaatsen waar er anders geen internet is
- dial up -> goedkoop gebruikt telefoonlijn en modemm handig tijdens het reizen maar traag 

### business netwerken
- dedicated leased line -> gehuurde lijnen binnen een ISP zijn netwerk om offices te verbinden meestal maandelijks of jaarlijks betaald
- Metro Ethernet -> ethernet WAN -> vergroot lan access technology naar WAN
- business DSL -> vaak Symmetrisch voor gelijke download en upload snelheid
- sattelite -> wanneer wired niet gaat
### convergerende netwerken
vroeger ging alles via andere kabels zoals video internet en telefoon nu niet meer veel meer gaat via dezelfde lijnen

## reliable networks
er zijn vier karakteristieken waar we aan moeten denken/
- fault tolerance
- schaalbaarheid
- QoS
- security

### fault tolerance
fault tolerance betekent dat als er iets stopt met werken de schade gelimiteerd blijft een voorbeeld is een packet switched network
dit zorgt ervoor dat alles opgebroken word in paketten die een andere weg kunnen nemen dus als er een router stuk gaat neemt het gewoon een andere weg
![[Pasted image 20250923153454.png]]

### schaalbaarheid
een schaalbaar netwerk kan snel uitgebreid wordden zonder de performantie van andere delen te beinvloeden
![[Pasted image 20250923153548.png]]
### quality of service
dit is de praktijk waarbij we zorgen dag bepaalde apparaten packets in memory kunnen bijhouden todat de juiste resources beschikbaar zijn zo kunnen we prioriteiten stellen bijvoorbeeld
wanneer de telefoon lijn hapert voelen we dit maar als dit gebeurt bij een email merken we er eigenlijk niks van

### security
dit is zowel fysiek ervoor zorgen dat niemand zomaar het netwerk op kan

maar ook de informatie zelf
3 voornaamste criteria:
- confidentiality -> alleen de mensen die aan de data mogen kunnen eraan
- integriteit -> de data is niet aangepast tijdens de transfer
- beschikbaarheid -> je kan er tijdig en reliably aan de info
## trends
- byod -> mensen willen hun eigen apparaten gebruiken
- online samenwerking -> er gebeurt meer en meer samen werking over dingen zoals teams
- video communicatie-> meer en meer mensen bellen met webcam
- cloud -> meer apparaten worden gehuurd uit grote datacenters waarbij er geconnecteerd word met ssh
	- public: kan iedereen gebruiken gratis of tegen betaling
	- private: voor een specifieke organisatie 
	- hybrid een mix van beiden maar distinct verschillende services
	- community een public cloud maar specifiek gemaakt naar de noden van de community die het gebruikt
- thuis -> meer en meer mensen hebben domotica en apps die bepaalde dingen regelen
- powerline -> dit zijn apparaten die een signaal doorgeven via de stroom binnenshuis handig om internet te verlengen -> kabels zijn nog steeds beter maar soms gaat het niet of is het te duur
- 

# cisco samenvatting
