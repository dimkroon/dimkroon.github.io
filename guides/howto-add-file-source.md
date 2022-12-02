### Add a file source to Kodi

File sources can be of various types. You can add sources on network shares, 
like your NAS, WEBDAV, FTP or sources on plain web servers. The latter is what
we are going to do in this how-to. We are going to add the web directory with 
the add-on zips on this website as a file source, so you can install the 
add-ons from Kodi without having to download them.

&nbsp;
![img select settings](/assets/images/kodi-home-select-settings.png)

First, go to the home screen in Kodi and click on settings

&nbsp;
![img select filemanager](/assets/images/kodi-settings-select-filemanager.png)
In settings, select filemanager

&nbsp;
![img select add source](/assets/images/kodi-filemanager-select-add-source.png)
In file manager select 'Add source'. If you use a keyboard or remote press
Enter or OK. If you use a mouse, you have to double-click.

&nbsp;
![img enter source](/assets/images/kodi-dlg-add-file-source-enter-source.png)
You could press the 'Browse' button to find a file source, but for us it is
much easier to directly enter the url to the web directory. So click on the 
input field that now shows '\<None>'.

&nbsp;
![img enter source location](/assets/images/kodi-enter-file-source-location.png)
An on-screen keyboard pops up where you can enter the url.
Enter 'https://dimkroon.github.io/kodi-addons'
And click 'OK'

&nbsp;
![img select source name](/assets/images/kodi-dlg-add-file-src-select-name.png)
You will now see the web address in the paths field. 

In the input field below you can give the file source a name. This is the name 
that will be show in the file browser. You can give it any name you like, but
it's best to give it a good descriptive name. Kodi has alread already named the
resource 'kodi-addons', but that does tell much about the origin of the 
add-ons. 

Better give a new name. Click on the entry field to show the on-screen 
keyboard. Let's name it 'dimkroon.github'. 

&nbsp;
![img dlg ok](/assets/images/kodi-dlg-add-file-src-select-ok.png)
Now the dialog should look like this. Clik 'OK' to confirm and add the source.
If everything is OK Kodi will return to the filemanager. 

If Kodi fails to gain access to the new source it will show a dialog to ask 
you whether to add the source anyway. If Kodi is connected to the internet it 
should not fail. Check the web address you have entered and try again. If kodi 
can still not connect to the web resource, and you are sure Kodi is correctly
connected to the internet, you can try to enter the same web 
address (https://dimkroon.github.io/kodi-addons) in a webbrowser on a normal
computer, just to check if the website is up.

&nbsp;
![img file mngr new src](/assets/images/kodi-filemanager-with-new-source.png)
Now you will see the newly added source in file manager.

You can double-check if it works by selecting it and press OK/Enter (or 
double-click with the mouse). You wil now see the contents of the web directory,
which is most likely just a few Kodi add-on zips.

Mind however, that we have just added a file source, not a repository. A 
repository can automatically update add-ons depending on the addon version and 
Kodi version, but a file source is nothing more than a place where Kodi can 
access files. The addons found here can be manually installed as zip file and
are to be manually updated.

