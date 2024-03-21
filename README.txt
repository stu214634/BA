

Diese Vorlage ist für die Verwendung mit pdflatex vorgesehen.

Empfohlenes Vorgehen für Grafiken:
-------------------------------------------------------------------------------------
Grafiken nach Möglichkeit im Vectorformat erstellen. Da mit pdflatex kompiliert 
wird muss dafür pdf genutzt werden. Adobe Illustrator oder Inkscape können direkt
im PDF Format speichern. Es ist darauf zu achten PDF 1.4 (Ab Acrobat 5.0) zu nutzen 
um pdflatex Warnungen zu vermeiden.

Wenn im Rasterformat gespeichert werden soll, die Grafiken in Photoshop laden, und 
unter Bild vergrößern 300dpi und die entsprechende Bildbreite einstellen. Dafür sollte
eine Zentimeter Angabe genutzt werden, was eine Auflösung von deutlich über 1500px zur 
Folge hat. Im tex File kann dann die Grafik ohne Angabe einer Größe oder Skalierung
genutzt werden, so werden häßliche tex Skalierungen verhindert.




Beachte:
-------------------------------------------------------------------------------------
ftp://ftp.dante.de/tex-archive/info/l2tabu/german/l2tabu.pdf