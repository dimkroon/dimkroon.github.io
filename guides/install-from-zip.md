### Install an addon from zip file

There are various ways to install an add-on in Kodi. The most convenient 
method is to install from a repository. Another way is to manually install an 
addon packed as a zip file, and that's actually quite simple as well. Add-ons 
served on this site are all available as zip file. In this how-to we will 
install such an add-on as zip file.

In order to allow installing add-ons from zip file, ensure you have 
'settings -> system -> addons -> unknown sources' enabled in Kodi. Click for 
details on 
[how to enable installing from unknown sources](/guides/enable-unknown-sources.html).

Now you have to obtain the zipped addon. For the addons served here, there are
basically two ways to do that.
* The first method is to manually download the zip and save it to a location 
  that is accessible by Kodi. The local file system of your Kodi device will 
  do nicely, but on some devices that may not be that easy. Alternatively you 
  can save the zip to a network share, like your NAS.
  Download the zip file from the GitHub releases page of the addon, or from 
  [the addons directory](/kodi-addons) on this website. 
  
* The second method is to add {{ site.url }}/kodi-addons as a file 
  source to Kodi's filemanager. This way you have direct access to the zip files
  served on this website. Click for detailed instructions on [how to add a file 
  source](/guides/howto-add-file-source.html)

&nbsp;
![img select settings](/assets/images/kodi-home-select-settings.png)
Start installation by selecting settings on the home screen.

&nbsp;
![img select settings](/assets/images/kodi-settings-select-addon.png)
In settings, select 'Addon' to open the addon browser.

&nbsp;
![img select settings](/assets/images/kodi-addonbrowser-select-install-zip.png)
In the add-on browser select 'Install from zip file'. You will be presented 
with a dialog informing you that add-ons installed this way will not 
automatically update. Keep that in mind and click 'Yes' to proceed.

&nbsp;
![img select settings](/assets/images/kodi-dlg-install-zip-select-github.png)
A file browser dialog will open. Use this to locate the zip file if you have 
just downloaded it manually. If you have followed the instructions at 
[how to add a file source](/guides/howto-add-file-source.html), you'll find 
a source named dimkroon.net in the file browser. Select that to open the
web directory.

Navigate to the zip file you want to install and click, or press enter. The 
add-on will now install. Kodi will automatically download and install 
dependency that are not yet present on your systeem. The time to completely 
install the addon varies depending on the number of packages it needs to 
download. 

When installing has finished Kodi will show a notification of either 
success, or failure. Failure is most likely due to an error in the add-on, or 
in the way it is packed. Please file an issue on GitHub if that happens and do 
not forget to add the debug log.

#### Note 
  Ensure to restart Kodi before you try to install an add-on again after a
  failure. Even if the add-on is fixed Kodi will continue to report the same
  error until you restart.




