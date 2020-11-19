

##  Chromium OS, het open-sourcealternatief voor Chrome OS

[https://helpdeskgeek.com/virtualization/how-to-install-chrome-os-in-vmware/](Lichtgewicht en goedkoop)

Google Chromebooks bieden een geweldig, laagdrempelig alternatief voor een volwaardige Windows-laptop. 
met toegang tot Google Documenten en Android-apps kunnen Chromebooks veel worden gebruikt, )
of het nu voor werk of plezier is. Voordat u iets koopt, kunt u de Chromebook-ervaring proberen om te zien of deze geschikt voor u is.
Het is heel goed mogelijk om de Chromebook-ervaring als een virtuele machine in VMWare te proberen. 
Technisch gezien moet u Chromium OS gebruiken, het open-sourcealternatief voor Chrome OS. 
Het mist een paar functies, maar het is verder identiek en zou je een voorproefje moeten geven van de Chromebook-ervaring.

## Wat is Chromium OS?
Open-sourcefans weten misschien al dat de Google Chrome-browser is gebaseerd op een project met de naam Chromium. 
Hoewel de code voor Chrome zelf niet wordt gedeeld, zijn grote delen ervan gebaseerd op Chromium, waardoor Google andere, 
alleen Chrome-secties van code kan 'vergrendelen'.Hetzelfde proces is van toepassing op Chromebooks, 
waarop Chrome OS wordt uitgevoerd, op basis van het bredere Chromium OS-project. 
Veel van de code is hetzelfde, maar Chrome OS bevat een paar extra functies, 
zoals ondersteuning voor Android-apps, die je niet zult vinden in Chromium OS.
Chrome OS kan niet worden gedownload, dus niet-Chromebook-gebruikers kunnen het niet rechtstreeks proberen. 
De redenen hiervoor zijn deels commercieel: Google wil tenslotte dat u zijn Chromebooks koopt.

Gelukkig is Neverware CloudReady een project dat de Chromium OS-basiscode gebruikt en extra ondersteuning 
toevoegt om het een bruikbaarder besturingssysteem te maken op niet-Chromebook-apparaten.
U kunt deze editie van Chromium OS rechtstreeks op uw pc of laptop installeren, 
maar u moet de Neverware-lijst met ondersteunde apparaten controleren om te controleren 
hoe goed uw apparaat wordt ondersteund voordat u begint. In plaats van dit te doen, zullen 
we onderzoeken hoe u CloudReady Chrome OS in plaats daarvan als een virtuele VMWare-machine kunt installeren.

## Installeer Chrome OS op VMWare   CloudReady OVA-bestand= CloudReady-Home-v83-x64.ova
Met VMWare kun je een virtuele machine draaien, met zijn eigen geïsoleerde virtuele hardware en opslag, 
bovenop je bestaande besturingssysteem. Als u bijvoorbeeld Ubuntu in Virtualbox installeert, 
krijgt u toegang tot Linux bovenop Windows of macOS.
U kunt dit tijdelijk doen om een nieuw systeem uit te testen of om gedurende een langere periode 
twee besturingssystemen tegelijkertijd te laten draaien. Dankzij Neverware CloudReady kun je de 
Chromebook-ervaring testen en uitproberen zonder je eraan te binden.

U moet eerst VMWare Workstation Player downloaden en installeren, beschikbaar voor gratis, 
niet-commercieel gebruik op Windows en Linux. Download na installatie de VMWare-afbeelding voor CloudReady naar uw pc. 
U moet er ook voor zorgen dat virtualisatie is ingeschakeld in uw BIOS / UEFI-instellingen.
Klik in VMWare Workstation Player op Player> File> Open. Zoek het CloudReady OVA-bestand, selecteer het en klik op Openen.

[CloudReady OVA-bestand= CloudReady-Home-v83-x64.ova](https://cloudreadykb.neverware.com/s/article/Download-CloudReady-Image-For-VMware)



