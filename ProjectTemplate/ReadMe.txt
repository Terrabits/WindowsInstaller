Working on some sort of intuitive installer generator, where you drag & drop files into position in various folders to build your installer.

Assumptions:
- Always installs to WINDOWSVOLUME (generally C:\, but not always)
- Special folders denoted with brackets (ie [ProgramData])
- Files in special folders that start with underscore are ignored (ie _Path.json)
- Special files used to add information (ie Settings.json, _Path.json, etc)
- UpgradeGuid added to Options after first installer is generated