jDiskMark is a disk io utility written in java. 


== Builds == 

https://sourceforge.net/projects/jdiskmark/


== Usage ==

1. Requires java 8.

2. to run:
    
   $ java -jar jDiskMark.jar

   On windows double click executable jar file.


== Release Notes ==

v0.1
 - initial release

v0.2
 - auto generate zip release ie. jdiskmark-v0.2.zip
 - added tabbed pane near bottom to organize new controls
 - format excessive decimal places
 - show recent runs (not persisted)
 - default to nimbus look and feel

v0.3
 - persist recent run with embedded derby db
 - remove "transfer mark number" from graph
 - changed graph background to dark gray
 - resizing main frame stretches tabbed pane instead of empty panel

v0.4e (evaluation)
 - updated eclipselink to 2.6 allows auto schema update
 - improved gui initialization
 - windows disk model via powershell query
 - linux disk model via "df /data/path" & "lsblk /dev/path --output MODEL"
 - osx disk model via "df /data/path" & "diskutil info /dev/disk1"

desired features
 - hard disk capacity and drive letter (windows)
 - auto clear disk cache linux
 - auto clear disk cache windows
