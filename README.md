# Sports Data Valley: Data Analytics Project

Neben meinem Master in Amsterdam durfte ich eine unbezahlte Projektarbeit für eine Sports Data Analytics Platform übernehmen. Diese bestand darin, Radsportdaten aus der Sport Data Valley API (plattformeigene API) mit Wetterdaten aus der API des Königlichen Niederländischen Meteorologischen Instituts (KNMI) zu kombinieren, um neue Erkenntnisse über den Einfluss von Gegen- und Rückenwind bei Radsportaktivitäten durch Datenvisualisierung zu gewinnen. Ich habe in Python programmiert und dabei hauptsächlich Bibliotheken wie NumPy, Matplotlib und Pandas verwendet.

Als Ergebnis (siehe Screenshot unten) konnte ich basierend auf den Längen- und Breitengraden der jeweiligen Radsportaktivitäten die Strecke des Fahrers nachkonstruieren, einschließlich seiner Fahrtrichtung (schwarze Pfeile im oberen Graphen) sowie die Windrichtung an den Standorten der Wetterstationen (blaue Pfeile im oberen Graphen).

Diese oben genannten Daten, in Kombination mit der Fahrtgeschwindigkeit des Fahrradfahrers und der Windgeschwindigkeit, sollten im unteren Graphen Aufschluss über den Einfluss der Windgeschwindigkeit auf die Radfahrgeschwindigkeit basierend auf der Fahrtrichtung und der Windrichtung geben. Auf dem unteren Graphen kann man somit sehen, in welchen Fahrtabschnitten der Radfahrer Rücken- und Gegenwind hatte (grüne und rote Balken) und inwieweit seine Fahrtgeschwindigkeit von der Windgeschwindigkeit beeinflusst wurde. Leider wurden die Daten zur Windgeschwindigkeit an den Wetterstationen nur in sehr großen Abständen gemessen (stündlich), wodurch die Datenbasis sehr klein war (siehe blaue Linie im unteren Graphen). Dies beeinflusst den Erkenntnisgewinn leider erheblich.

In diesem Repository finden Sie den Code zur Erstellung dieser Graphen. Leider funktioniert dieser nur mit einem Authentifizierungstoken, um die Sport Data Valley API zu nutzen. Leider ist meiner, den ich damals zur Erstellung des Projekts genutzt habe, abgelaufen.

![Endresult](https://github.com/Marpetel/Cycling_Data_Analytics_Project/assets/96209318/9da28811-358f-464c-a12c-e48cde2e3546)
