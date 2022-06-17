# Afkortingen

`BIOS`: Basic Input Output System - de traditionele *firmware* van een PC die in een chip op het moederbord (vaak een EEPROM of recenter een flash-geheugen) aanwezig is en o.a. verantwoordelijk is voor het vinden van de juiste opstartschijf. Hyper-V noemt dit **Generatie 1**-machines.

`UEFI`: Unified Extended Firmware Interface - een meer recente *firmware*  die in een chip op het moederbord (meestal een flash-geheugen) aanwezig is. Hyper-V noemt dit **Generatie 2**-machines.

`VM`: Virtuele Machine. Een verzameling instellingen zoals aantal CPU cores, hoeveelheid RAM, aangesloten schijven en schijf-controllers, start- en stop-acties, ...

`VHD`: Virtual Hard Disk. Een bestand dat kan beschouwd worden als een **dump** van een echte harde schijf. Met `diskmgmt.msc` kan je dit soort virtuele HD's ook echt aan je Windows OS toevoegen en in Verkenner gebruiken zoals een echte HD. Je kan zelfs een fysieke HD *exporteren* naar een VHD-bestand.

`VHDX`: Een modernere versie van VHD die beter omgaat met de schijfruimte. Vele nieuw gemaakte VHD's zijn aanvankelijk immers grotendeels leeg en zouden dan nodeloos veel schijfruimte innemen. VHDX-bestanden kunnen dynamisch groeien naarmate er meer bestanden op worden gezet.

`AVHDX`: Wanneer je controlepunten (snapshots) van schijven maakt, is het efficiënter om niet telkens een volledige kopie van een VHD te nemen maar om slechts het verschil (wat er veranderd/toegevoegd) is apart op te slaan in `.avhdx`-bestanden. Telkens je overschakelt naar een ander controlepunt, zal Hyper-V m.b.v. de verschillende `.avhdx`-bestanden zorgen dat de VHD geconfigureerd wordt op het door jouw gekozen controlepunt.

`ISO`-bestanden: schijf-images (*dumps*) van wat traditioneel optische media waren zoals CD's en DVD's. Het is dus eigenlijk een soort virtuele CD of DVD.

`Installatie-media`: Vroeger kon je  een Microsoft Windows installatie-CD/DVD kopen (waarschijnlijk nu nog), tegenwoordig werkt bijna iedereen met van het Internet gedownloade `.iso`-bestanden die op een USB-stick kunnen **gebrand** worden. (De term **branden** is nog afkomstig van de tijd dat CD's en DVD's met een LASER-straal op een optische schijf konden worden *gebrand*.) Andere installatie-media van OS's die mogelijk zijn: floppy disks (hopeloos verouderd), rescue-partities op laptops (helaas vaak met nutteloze/irritante custom software waarvoor de laptop-fabrikant is betaald geworden, je kan dit dus gerust beschouwen als promotie/reclame die voorgeïnstalleerd op je laptop aanwezig is - een ethisch twijfelachtige praktijk!), netwerk-installs, ...






