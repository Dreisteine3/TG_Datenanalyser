# Datenanalyse der 2023 Spot-Preisen
Um neue Tarifkonzepte zu entwickeln, auf EPEX-Spot-Price bezogene Endkundenpreise sind durch Datenanalysemethodik analysiert und visualisiert, sodass die Regeln, wie die Börsenpreis sich verhalten, gefunden werden können. Das führt zu der wichtigen Referenz für 3-Stufen Tarif Design, weil der neue Tarifmodell daran ausrichten soll, den Strompreis auf Spot-Markt widerzuspiegeln. <p>
Um die Spot-Preise intuitiver zu zeigen, sind Streudiagramme mit verschiedenen Zeitscala abgebildet. Dateninput ist Endkundenpreis, der aus 4 Bestandteile besteht: Börsenpreis, Netzentgelte, Steuer und Gewinnmarge. Die Zusammensetzung ist in folgender Formula beschrieben:
$$ 
\begin{aligned}
Endkundenpreis =& 
    [Börsenpreis * Gewinnmarge + (Netzentgelt + Stromsteuer \\
    &+ OffshoreUmlage + KWKGUmalge + Konzessionsabgabe \\
    &+ Messungspreis + §19 StromNEVUmlage)] * Mehrwertsteuer 
    \end{aligned}
$$
Die Werte der Bestandteilen sind im folgenden Bild gezeigt.

<img src=https://www.bdew.de/media/original_images/2023/10/23/grafik_strompreis-haushalte_APBXgeb.jpg width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 1. Strompreis Bestandteile 2023 für Haushalte 
</p>
 
## Streudiagramme
Die Punkte in den Streudiagrammen zeigen die Endkundenpreise im Tagverlauf in verschiedenen Zeiträume, wie z.B. jährlich, monatlich und saisonal.
### Jährlich
<img src="https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/year.png" width="1000">

<p style='text-align: center; font-weight: bold;'>
    Bild 2. tägliche Endlundenpreise in 12 Monate in 2023
</p>
<p>Es ist deutlich, dass Preiswerte von Januar bis März (dunkel-blau Punkte) sind höher als die Preise von Juni bis Oktober (hell-grün Punkte), die Erzeugungsperiode der Solarenergie entspricht. In Juli/August gibt's extreme negative Preise, und in Oktober/November gibt's extreme hohe Preise. </p>
<p>Um die Unterschiede in verschiedenen Monaten besser abzubilden, sind folgende monatliche Grafiken zu zeigen.</p>

### Monatlich
In folgenden Grafiken sind die Strompreise in jedem Monat in gleicher Farbe wie das jegliche Monat in jährliche Grafik geplottet, wovon die Daten am Wochenende getrennt und in roter Farbe markiert sind.
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_1.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 3. tägliche Endlundenpreise in Januar, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_2.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 4. tägliche Endlundenpreise in Februar, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_3.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 5. tägliche Endlundenpreise in März, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_4.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 6. tägliche Endlundenpreise in April, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_5.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 7. tägliche Endlundenpreise in Mai, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_6.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 8. tägliche Endlundenpreise in Juni, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_7.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 9. tägliche Endlundenpreise in Juli, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_8.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 10. tägliche Endlundenpreise in August, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_9.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 11. tägliche Endlundenpreise in September, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_10.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 12. tägliche Endlundenpreise in Oktober, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_11.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 13. tägliche Endlundenpreise in November, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/month_12.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 14. tägliche Endlundenpreise in Dezember, 2023
</p>
Angesichts der Unterschiede zwischen Stromerzeugung und Verbrauch, sind die Preisdaten in Sommer (April bis Oktober) und Winter (November bis März) getrennt und gezeigt.
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/hourly_prices_summer_2023.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 15. tägliche Endlundenpreise in Sommer, 2023
</p>
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/hourly prices/hourly_prices_winter_2023.png' width=1000>
<p style='text-align: center; font-weight: bold;'>
    Bild 16. tägliche Endlundenpreise in Winter, 2023
</p>

## K-Means Clustering
<p>Um die drei Stufen zu bestimmen, sind die sogenannte 'Clusters' zu finden, wo die Daten am meisten sich versammeln. Hier ist K-Means Algorithmus zu verwenden, der eine Art der Machine-Learning Methode ist.</p>
<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/k-means.png' width=500>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 17. Darstellung K-Means
</p>

<p><i>Die Idee von <strong>K-Means</strong> ist ziemlich einfach und intuitiv. Der erste Schritt besteht darin, drei Zentroiden <strong>zufällig</strong> zu definieren, denen wir 2 Bezeichnungen zuordnen, z. B. 1, 2 in (b). Dann schauen wir uns für jeden Punkt die Entfernung zu den 2 Zentroiden an und verbinden den Punkt mit dem nächstgelegenen Zentroiden und dem entsprechenden Label. Dies entspricht einer Beschriftung unserer Daten.

Schließlich berechnen wir 2 neue Zentroiden, die die Schwerpunkte jeder beschrifteten Punktwolke sein werden. Diese Schritte werden so lange <strong>iterriert</strong> oder wiederholt, bis die neuen Zentroide sich nicht mehr von den vorherigen unterscheiden. Das Endergebnis ist in der Abbildung (f) zu sehen. </i></p>

In KMeans Modul von Python ist dieses Prozess durch die Methode <table><tr><td bgcolor=lightgray><font face='Courier New'>kmeans = KMeans(n_clusters=n_clusters, random_state=0).fit(data)</font></td></tr></table> realisiert, wo <font face='Courier New'>n_clusters</font> gibt die Anzahl der Clusters an.

Für unsere Situation ist es etwa unterschiedlich: wir wollen nicht ein Zentrumpunkt von einer Punktgruppe zu finden, sodern eine Zentrumlinie (Preisstufen) für alle Punkte (einzelner Preisdaten) in 24 Stunden zu finden. Deswegen hat es sich in dem Code so verändert: jeder Punkt (Preisdaten) wird 24 Mal widerholt und kann deswegen als eine horizontale Linie betrachtet. Dann ist der umgestalteter Datensatz (ein 24 Reihen * n Spalten array) in Methode KMeans.fit() verwendet und dadurch können die drei Stufen als Cluster-Linien festgelegt werden.
<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/center_lines_for_kmeans.png' width=700>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 18. Darstellung der Verarbeitung der Daten für K-Means
</p>

### Entfernung der Outliers
Weil es viele extreme Börsenpeise gibt, besonders in Sommer, ist es sinnvoll, bevor der Definition der 3 Stufen die Ausreißer, die sogenannte Outlier zu entfernen. Die Prinzip der Entfernung wird hier erklärt.
Zuerst sind die Daten zu KMeans.fit() eingespeist, wo der Parameter <font face='Courier New'>n_clusters</font> zu 1 eingestellt ist. Dann mit Funktion <font face='Courier New'>cdist</font> können die Entfernung zwischen Zentroid und allen Punkten berechnet. Danach ist eine Grenze, sogenannt 'threshold' eingestellt. Alle Punkte, deren Entfernungen mit Zentroid größer als diese Grenze sind, werden als Outliers betrachtet und für 3-Stufen Festlegung gefiltert.

| | Sommer | | Winter | |
| --- | --- | --- | --- | --- |
| | <strong>Wochentag | <strong>Wochenende | <strong>Wochentag | <strong>Wochenende |
| ohne Filter | 3648 | 1488 | 2592 | 1032 |
| mit Filter | 3385 | 1422 | 2387 | 968 |
| gefiltert | -7.2% | -4.4% | -7.9% | -6.2% |
<p style='text-align: center; font-weight: bold;'>
    tabelle 1. gefilterte Datenmenge und Anteile 
</p>

| | Sommer | | | Winter | | |
| --- | --- | --- | --- | --- | --- | --- |
| | Wochentag | Wochenende | gesamt | Wochentag | Wochenende | gesamt |
| Standard Abweichung (ohne Filter) | 5.0 | 6.14 | 5.60 | 6.23 | 5.97 | 6.32 |
| Standard Abweichung (mit Filter) | 3.41 | 5.0 | 4.29 | 5.33 | 5.52 | 5.55 |
<p style='text-align: center; font-weight: bold;'>
    tabelle 2. Vergleich der Standard-Abweichung ohne und mit Filter von Outliers 
</p>

## Festlegung der drei Stufen
Nach Filtern von Outliers ist KMeans wieder für die Festlegung der 3 Stufen benutzt. Hier sind <font face='Courier New'>n_clusters = 3</font> eingestellt, und die 'saubere Daten', d.h. die gefilterte Daten ohne Outliers, werden als Input der K-Means Methode verarbeitet.

### Variante 1: drei Stufen sind saisonal fest
<p>In dieser Variante ist die Definition der 3 Stufen auf die Daten von dem ganzen Sommer und Winter basiert und festgelegt. </p>
<p>Sommermonate in 2023: April, Mai, Juni, Juli, August, September, Oktober; </p>
<p>Wintermonate in 2023: januar, Februar, März, November, Dezember. </p>

<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/price levels/Levels for Summer_2023.png' width=1000>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 19. drei-Stufen für Sommer, 2023
</p>
Nach Outliers entfernt werden, dienen negative Preise und extreme hohe Preise nicht zu der Festlegung der 3 Stufen und dadurch kann das Risiko der extremen Börsenpreisen vermieden werden.
<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/price levels/Levels for Winter_2023.png' width=1000>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 20. drei-Stufen für Winter, 2023
</p>
Die blaue Linien zeigen die 3 Clusters für alle Preisdaten am Wochentag, whärend die rote Linien zeigen die 3 Clusters für alle Preisdaten am Wochenende. Es macht Sinn, dass alle der 3 roten Linien niedriger als blaue Linien sind, weil am Wochenende sind die typische 2 Verbrauchs- und Börsenpreisspitzen (eine am Morgen und eine am Abend) nicht so deutlich wie am Wochentag.

### Variante 2: drei Stufen sind monatlich fest
Um die Unterschiede mit saisonalen Tarifstufen zu vergleichen, sind Preisstufen monatlich festgelegt.
<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/price levels/Levels for Month_1_2023.png' width=1000>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 21. drei-Stufen für Januar, 2023
</p>


### Variante 3: drei Stufen sind täglich fest
## Auslösung der drei Stufen
Für jede Variante kann man eine Stufe aus 3 optionen auswählen, die am nähsten mit Börsenpreis ist.
<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/trigger examples/weekday/trigger 2023-01-16.png' width=1000>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 22. Tarifauslösung am Beispieltag (2023-01-16, Winter, Wochentag)
</p>
<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/trigger examples/weekend/trigger 2023-12-23.png' width=1000>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 23. Tarifauslösung am Beispieltag (2023-12-23, Winter, Wochenende)
</p>
<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/trigger examples/weekday/trigger 2023-08-01.png' width=1000>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 24. Tarifauslösung am Beispieltag (2023-08-01, Sommer, Wochentag)
</p>
<div style="text-align: center;">
<img src='https://raw.githubusercontent.com/Dreisteine3/TG_Datenanalyser/main/Pictures/trigger examples/weekend/trigger 2023-07-01.png' width=1000>
    </div>
<p style='text-align: center; font-weight: bold;'>
    Bild 25. Tarifauslösung am Beispieltag (2023-07-01, Sommer, Wochenende)
</p>