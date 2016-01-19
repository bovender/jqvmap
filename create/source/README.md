German ZIP code (PLZ) maps
==========================

The data files in this directory are from two sources:

[arnulf.us/PLZ][1]

    germany_plz.dbf
    germany_plz.shp
    germany_plz.shx

[www.suche-postleitzahl.org][2]

    plz-2stellig.dbf
    plz-2stellig.prj
    plz-2stellig.shp
    plz-2stellig.shx

These files are used under the [Open Database License](http://www.openstreetmap.org/copyright).

---

Die o.g. Dateien enthalten die Quelldaten für zwei verschiedene 
[JQVMap](http://jqvmap.com)-Karten. Die erste von [arnulf.us][1] umfaßt 
alle Postleitzahlen mit Stand 1999. Dementsprechend detailliert fällt 
die Karte aus, und das Rendern der SVG-Datei im Browser dauert lange. 
Außerdem ist die Karte für manche darzustellende Datensätze wohl zu 
kleinteilig.

Dankenswerterweise stellt [suche-postleitzahl.org][2] auch Shape-Dateien 
mit den Bereichen der ersten beiden PLZ-Stellen zur Verfügung. Das 
dürfte für viele Anwendungsfälle der bessere Datensatz sein. Die Karte 
wird relativ schnell gerendet.

[1]: http://arnulf.us/PLZ
[2]: http://www.suche-postleitzahl.org

# vim: et sts=2 sw=2 ai fo+=tcoqn tw=72
