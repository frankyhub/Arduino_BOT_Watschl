# Arduino_BOT Joe Watschl




![image](https://github.com/frankyhub/png/blob/master/Watschl.JPG)

[Bauanleitung](https://github.com/frankyhub/Arduino_BOT_Watschl/blob/main/Bauanleitung/Bauanleitung%20Jo%20Watschl.pdf)



Bauanleitung Jo Watschl

Stückliste
1	ABS Platte DINA4 2mm	
4	Platinenhalter (3D-Druck)	
4	Abstandshalter M3*25 Kunststoff	
		
1	Ardunio NANO	
4	SG90 Servo	
1	HCSR04 Ultraschallsensor	
1	LM 2596S Spannungsregler 5V	
1	9V Batterie mit Gehäuse	
		
	Schrauben	
10	M1.5*5	
6	M1.4*8	
12	M2*8	
18	M3*5	
8	M3*8 Senkkopf	
	Muttern	
6	M1.4	
12	M2	
8	M3 selbstsichernd	


Schritt 1: Die ABS-Platten lasern
Verwende die Vorlagen
-	2 x BeinV1.SVG
-	1 x DeckplatteV1.SVG
-	1 x GrundplatteV1.SVG
-	2 x FussV1.SVG
-	2 x FerseV1.SVG
Link: https://github.com/frankyhub/Arduino_BOT_Watschl/tree/main/Cutter

 
Laserdatei mit Reserve-Elementen (Bein und Ferse)

Schritt 2: Die Schenkel der Fersen und der Füße biegen und auf angegebenen Durchmesser aufbohren.

Füße: Beide Schenkel gleich lang, Innenmaß 37 mm
 
Bohrungen: 
 
Ferse biegen, beide Schenkel gleich lang:

 

Bohrungen: Für die 1,5mm Bohrungen des Servos, den Servo als Bohrschablone verwenden.
 


Schritt 3: Die Platinenhalter drucken
3D-Druckvorlage Link: https://github.com/frankyhub/openscad-Beispiele/tree/master/008%20Platinenhalter

 
Schritt 4: Die Schrittmotoren auf die Grundplatte und an die Fersen montieren und verschrauben (alternativ kleben). Ferse und Schenkel verschrauben. Die Teile müssen beweglich bleiben, so dass der Schrittmotor den Schenkel bewegen kann.

 
 
Schritt 5: Den Ultraschallsensor an die Deckplatte montieren (alternativ kleben).

Schritt 6: Den Arduino NANO auf die Deckplatte montieren.

 

Schritt 7: Den Batteriehalter an die Grundplatte montieren (alternativ kleben).

 

Schritt 8: Die Schrittmotoren, den Ultraschallsensor und den Batteriehalter nach Schaltplan verdrahten.
Link: https://github.com/frankyhub/Arduino_BOT_Watschl/tree/main/Schaltplan

 
Schritt 9: Das Programm in den Arduino NANO laden
Link: https://github.com/frankyhub/Arduino_BOT_Watschl/tree/main/Code

Schritt 10: Funktionstest

 

Fertig!



