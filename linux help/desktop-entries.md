# Desktop entries

### Structure

```
[Desktop Entry]  
Version=1.0
Name=Jawg Storage
Comment=Jawg Storage is an awesome back-end client that manages different geolocalized entities.
Exec=/home/jawg/storage/bin/storage.sh
Path=/home/jawg/storage
Icon=/usr/share/icons/jawgIcon.svg
Terminal=false
Type=Application
Categories=Utility;Application;Development;
```

* Version

Refers to the .desktop file version, not to the program version.

* Name

The name that should be displayed on the menu.

 * Exec

The full path to the executable.

* Path

The dir that will be set as current when the entry is run. You usually don't need to set it.

* Icon

The path to the icon file that will be used for the file.

* Mimetype

Specifies the kind of files that this program is able to open.

* StartupWMClass

Only needed for some programs, It is usually needed by java programs but only set it if you notice some problems.

### Where to put desktop entries

To use the desktop file they has to be put in `/usr/share/applications` for any user to be able to use it or to `~/.local/share/applications` if you just want it to be available for one user.

### More infos

For complete information about desktop entries the  Desktop Entries Specification is available [here](https://specifications.freedesktop.org/desktop-entry-spec/latest/).
