### Voeg een web url als bestandslocatie toe aan Kodi

Er zijn verschillende soorten bestandslocaties. Je kan locaties toevoegen van 
netwerk shares, zoals een NAS, WEBDAV, FTP en ook van een gewone webserver. 
Dat laatste is wat we gaan doen, maar de procedure voor andere types is 
nagenoeg hetzelfde. We gaan de folder met de zipbestanden op deze webserver  
toevoegen als bestandslocatie in Kodi, zodat je de addons kunt installeren 
zonder ze eerst te hoeven downloaden.

&nbsp;
![img select settings](/assets/images/kodi-home-select-settings.png)

Ga naar het Thuis scherm in Kodi en klik op Instellingen

&nbsp;
![img select filemanager](/assets/images/kodi-settings-select-filemanager.png)
In Instellingen, selecteer Bestandsbeheer

&nbsp;
![img select add source](/assets/images/kodi-filemanager-select-add-source.png)
In Bestandsbeheer select 'Locatie toevoegen'. Gebruik je aan toetsenbord of 
afstandsbediening, druk dan op Enter of OK. Als je een muis gebruikt dan moet 
je dubbel klikken.

&nbsp;
![img enter source](/assets/images/kodi-dlg-add-file-source-enter-source.png)
Je zou op 'Bladeren' kunnen klikken om de locatie op te zoeken, maar voor ons 
is het veel makkelijker om direct de url in te voeren.
Dus klik op het invoer veld waar nu '\<Geen>' staat.

&nbsp;
![img enter source location](/assets/images/kodi-enter-file-source-location.png)
Er wordt een on-screen toetsenbord getoond waar je het web adres kan invoeren.
Voer in: '{{ site.url }}/kodi-addons'
En klik op 'OK'

&nbsp;
![img select source name](/assets/images/kodi-dlg-add-file-src-select-name.png)
Je ziet nu het web adres in het invoerveld voor locaties.

In het invoerveld beneden kan je de web locatie aan naam geven. Dit is de 
naam die in Bestandbeheer getoond gaat worden. Je kan het elke willekeurige 
naam geven, maar het beste is om een goede beschrijving van de locatie te 
nemen. 

Kodi heeft de locatie al 'kodi-addons' genoemd, maar dat zegt weinig over 
de herkomst. We kunnen het beter een nieuwe naam geven. Klik op het invoerveld 
om het on-screen toetsenbord weer te geven en voer de naam 'dimkroon.github' 
in. 

&nbsp;
![img dlg ok](/assets/images/kodi-dlg-add-file-src-select-ok.png)
Het dialoogvenster moet er nu zo uit zien. Klik 'OK' om te bevestigen en de 
locatie toe te voegen. Als alles goed gaat dan gaat Kodi nu terug naar 
Bestandsbeheer. 

Als Kodi geen toegang kan krijgen tot de nieuwe locatie dan wordt er een 
dialoog getoond met de vraag om het evengoed toe te voegen. Als Kodi met 
internet verbonden is dan mag dit niet gebeuren. Controleer de url die je hebt 
ingevoerd en probeer het opnieuw.

Als Kodi nog steeds niet kan verbinden en je weet zeker dat de 
internetverbinding goed is, dan zou je kunnen proberen om op een 
normale computer hetzelfde web adres ({{ site.url }}/kodi-addons) in een 
webbrowser in te voeren, gewoon om te zien of de website werkt.

&nbsp;
![img file mngr new src](/assets/images/kodi-filemanager-with-new-source.png)
De neiuwe locatie is nu zichtbaar in Bestandsbeheer.

Je kan nogmaals controleren of het werkt door de locatie te selecteren 
(Dubbel-klik met een muis). Je zult dan de inhoud van de webfolder zien. 
Waarschijn slechts enkele addon zip bestanden.

#### Let op
Je hebt alleen maar een bestandslocatie toegevoegd, geen repository. Een 
repository kan automatisch addons updaten, afhandeklijk van de versie en de 
versie van Kodi, maar een bestandslocatie is niet meer dan een plek waar 
Kodi bestanden kan vinden. De addons die hiuer vindt moet je handmatig als 
zip bestand installeren en dienen handmatig ge-updated te worden.

#### Let op
Je kan niet zomaar elke web url aan Bestandsbeheer toevoegen en verwachten 
dat je de inhoud kan zien. Een webserver moet specifiek voor dit doel 
geconfigureerd zijn.


