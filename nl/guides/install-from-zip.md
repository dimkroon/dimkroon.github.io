---
description: Add-ons voor kodi door Dimitri Kroon
---

### Add-ons installeren via zipbestand

Er zijn verschillende manieren om in Kodi addons te installeren. Het meest 
eenvoudige is om te installeren van een repository. Een andere manier is om 
handmatig een zipbestand te installeren, en dat is eigenlijk ook helemaal 
niet moeilijk. De addons op deze website zijn allemaal beschikbaar als 
zipbestand.

Om zipbestanden te kunnen installeren moet je ervoor zorgen dat je
'instellingen -> systeem -> addons -> Onbekende bronnen' hebt ingeschakeld. 
Klik voor details op
[onbekende bronnen toestaan](/nl/guides/enable-unknown-sources.html)

Nu moeten we de addons als zip file bemachtigen. Voor de addons op deze 
website zijn er grofweg twee methodes.
* Als eerste kun je handmatig het zipbestand downloaden en ergens opslaan 
  waar het vanuit Kodi bereikbaar is. De lokale schijf van Kodi is 
  bijvoorbeeld prima, maar op sommige apparaten is dat niet zo makkelijk 
  toegankelijk. Als alternatief kan je de zip opslaan op een network share, 
  zoals je NAS.
  Download het zipbestand van de GitHub releases pagina van de addon, of van
  [de addons folder](/kodi-addons) op deze website. 
  
* De tweede manier is om {{ site.url }}/kodi-addons als een bestandslocatie 
  toe te voegen aan Kodi's Bestandbeheer. Op deze manier heb je direct 
  toegang tot de addons die op deze website beschikbaar zijn. Klik for 
  gedetailleerde instructies op 
  [url als bestandslocatie toevoegen](/nl/guides/howto-add-file-source.html).

&nbsp;
![img select settings](/assets/images/nl/kodi-home-select-settings.png)
Begin de installatie door in het thuis scherm op instellingen te klikken.

&nbsp;
![img select settings](/assets/images/nl/kodi-settings-select-addon.png)
In Instellingen, selecteer 'Add-ons' en de addon-verkenner zal openen.

&nbsp;
![img select settings](/assets/images/nl/kodi-addonbrowser-select-install-zip.
png)
In de Addon-verkenner selecteer 'Add-ons installeren via zipbestand'. Je zult 
nu een dialog venster te zien krijgen waarin je gemeld wordt dat addons die op
deze manier geïnstalleerd zijn niet automatisch worden bijgewerkt. Onthoudt 
dat en klik op 'ja' om door te gaan.

&nbsp;
![img select settings](/assets/images/nl/kodi-dlg-install-zip-select-github.png)
Er opent nu een bestandsverkenner. Gebruik dit om het zip bestand te vinden 
als je dat zojuist handmatig hebt gedownload.
Als je de instructies hebt gevolgd op 
[url als bestandslocatie toevoegen](/nl/guides/howto-add-file-source.html), 
dan zul je de locatie genaamd dimkroon.net in de verkenner aantreffen. 
Selecteer dat om web folder te openen.

Ga naar het zipbestand van de addon dat je wilt installeren en klik erop, of 
druk op Enter/OK. De addon zal nu worden geïnstalleerd. Kodi installeert 
automatisch alle afhankelijkheden die nog niet op je systeem zijn 
geïnstalleerd. Hoe lang het installeren duurt, hangt af van het aantal 
pakketten dat Kodi moet downloaden.

Wanneer de installatie klaar is krijg je een melding van òf succes, òf van 
een fout. Een fout is waarschijnlijk het gevolg van een fout in de addon, of 
van de manier waarop het is ingepakt. Als dat gebeurt, meldt dat alsjeblieft 
op github en vergeet niet een debug log mee te sturen.

#### Let op 
  Zorg ervoor dat je Kodi opnieuw opstart als er een fout is geweest met het 
  installeren van een addon. Zelfs als de addon hersteld is zal Kodi de 
  fout blijven geven totdat je herstart.




