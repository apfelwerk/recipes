# recipes
Autopkg Recipes

Ziel: SCRIPT AUTOMATISIERUNG DES PKG AM JAMF SERVER 

1. Autopkgr: NameProgram_VersionNummer.pkg

Überblick Fälle Programme beim Herunterladen:
 
- .dmg ---> .app -----> .pkg mit Version : Google Chrome
- .dmg ---> .pkg -----> .pkg mit Version : Cisco Webex Meetings
- .pkg ---------------> .pkg mit Version : Zoom
- .zip ---> .app -----> .pkg mit Version : Visual Studio Code

Je nachdem welche Datei man herunterlädt, kann man das Script anpassen.

2. PKGs Signieren
3. JSSImporter 