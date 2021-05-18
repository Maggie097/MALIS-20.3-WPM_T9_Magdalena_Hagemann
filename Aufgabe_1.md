Aufgabe MALIS 20.3 
WPM_T9.1: Data Science / Data Librarianship / IT-Praxis
Autorin: Magdalena Hagemann
Datum: 16.05.2021


**1.	Einführung:**

Das GestDiab-Register des Forschungsinstituts der niedergelassenen Diabetologen (winDiab) bildet den Versorgungsprozess schwangerer Frauen mit Gestationsdiabetes, Typ-1- und Typ-2-Diabetes in Diabetes-Schwerpunktpraxen ab. Die Patientinnen-Daten werden hierbei von den teilnehmenden Praxen eigenständig in das EDC-System secuTrial eingetragen. Diese Daten werden jährlich von den dafür zuständigen Mitarbeitenden ausgewertet und den Praxen in Form eines Berichts sowohl für die eigene Analyse als auch für den Vergleich mit dem Gesamtkollektiv zur Verfügung gestellt. Ziel des GestDiab-Registers ist es, auf Grundlage der Ergebnisse der Datenauswertungen die Behandlungsprozesse diabeteserkrankter schwangerer Frauen in den Praxen zu optimieren und eine verbesserte Diabetesprävention nach der Entbindung auf den Weg zu bringen.

**2.	Datenintensive Prozesse im Arbeitsalltag**

**2.1	Forschungsdatenmanagement**

Das Forschungsdatenmanagement ist der Bereich, der die datenintensivsten Prozesse beinhaltet, schließlich dreht sich hier alles um die Erhebung, Verarbeitung, Auswertung, Dokumentation, Veröffentlichung, Archivierung und Nachnutzung von Daten – und zwar „alle(r) digital vorliegenden Daten, die während des Forschungsprozesses entstehen oder ihre Ergebnisse sind.“[1]  Dazu gehören im Arbeitsalltag unter anderem die Stammdaten der Patientinnen (Geburtsdatum, Gewicht, Angaben zu Schwangerschaftswoche etc.), Messdaten und Laborwerte. Die erfassten Behandlungsdaten sind dabei in vier Bereiche unterteilt: Grunddaten, Behandlungsdaten, Entbindungsdaten und postpartale Daten. 

Die Erfassung der Daten erfolgt durch die Praxen selbst, welche das Register über das Electronic-Data-Capture-System secuTrial befüllen. Die Auswertungen wiederum erfolgen durch den Export in eine Excel-Tabelle, in welcher die Daten jährlich zusammengeführt werden. Die ausgewerteten Daten werden regelmäßig in Form von Diagrammen und Infografiken visualisiert und in diversen Publikationen veröffentlicht sowie zur Nachnutzung bereitgestellt.

**2.2	Management von Dateien und Ordnern**

Im Bereich Wissenschaftliche Koordination und wissenschaftliches Projektmanagement fallen vielfältige Aufgaben an, die datenfokussiert sind. Die herausforderndste ist das Management von Ordnern und Dateien, welche von allen Mitarbeitenden genutzt werden. Die Fülle an Ordnern, Unterordnern und Dateien erfordert eine gut durchdachte Struktur, sinnvolle Benennung und ständige Kontrolle der Versionsverläufe sowie Überprüfung der Aktualität und ggf. Verschiebung von Dateien in Archiv-Ordner.

Für das kollaborative Arbeiten wird der cloudbasierte Dienst Microsoft SharePoint genutzt. Mitarbeitende können also Dateien hier ablegen, auf welche dann auch alle anderen, die dazu berechtigt sind, Zugriff haben. Auch das gemeinsame Arbeiten an Dokumenten ist mit SharePoint möglich.

Eine Problemquelle bei diesem System ist die Tatsache, dass viele verschiedene Nutzer*innen verschiedene Gewohnheiten besitzen, wie sie Daten ablegen und diese benennen. Hier bewähren sich die auf forschungdaten.info vorgeschlagenen Tipps für die Organisation von Daten[2]:

1.	Bestehende Best Practices nutzen
2.	Daten in Ordnern ablegen
3.	Systematische, inhaltsbezogene Ordnerbenennung verwenden
4.	Nicht mehr als drei Unterordner-Ebenen verwenden
5.	Nach Projektende prüfen, was noch gebraucht wird
Wichtig aber ist, dass alle Beteiligten diese Prozesse verinnerlicht haben, daher ist es ratsam, ein SOP-Dokument zu erstellen, in welcher die Handhabung von Ordnern und Dateien dokumentiert ist. Dies ist nicht zuletzt sinnvoll beim Wechsel von Mitarbeitenden.

**2.3	Pflege von Teilnehmerdaten**

Zu den am GestDiab-Register teilnehmenden Praxen existieren ebenfalls zahlreiche Daten, die gepflegt werden müssen. Diese sogenannten Teilnehmerdaten bestehen unter anderem aus einer Praxis-ID, dem Datum des Teilnahmestarts am Register, den Namen der Praxis, den Namen der Prüfärzt*innen, Kontaktdaten, Kontodaten und anderen. 

Aktuell werden die Teilnehmerdaten in einer Excel-Tabelle erfasst und gepflegt. Zudem gibt es zu jeder Praxis-ID einen eigenen Ordner, in welchem jeweils die Vertragsdokumente und andere Formulare (z. B. Lebensläufe, Infos zur Bankverbindung oder Info über die Mehrwertsteuerpflicht) liegen sowie die Kommunikation mit der Praxis dokumentiert ist.

Bei diesem datenfokussierten Prozess wäre jedoch eine andere Art der Datenerfassung und Datenpflege wünschenswert. Daher gehe ich im Folgenden auf das Optimierungspotential bei diesem Fall ein.

**3.	Prozessvereinfachung am Beispiel der Pflege der Teilnehmerdaten durch Einsatz einer Datenbank**

Der Prozess der Eingabe und Verwaltung der Teilnehmerdaten ließe sich effizienter gestalten, wenn für die Pflege der Daten statt einer Excel-Tabelle eine Datenbank zum Einsatz käme. Vor allem in Anbetracht der Tatsache, dass in Zukunft immer mehr teilnehmende Praxen und daher immer mehr Daten hinzukommen, scheint Excel als Programm keine zufriedenstellende Lösung zu sein, denn mit der Zunahme von Daten fällt es immer schwerer, den Überblick zu behalten, woraus sich mögliche Fehlerquellen ergeben könnten. Auch wenn neu zu erfassende Informationen bei den Praxen hinzukommen, die neue Spalten in der Excel-Tabelle erforderlich machen, wird die Übersichtlichkeit gemindert. 

Die Zunahme an Daten bedeutet aber auch, dass das Excel-Dokument an einem bestimmten Punkt an seine Grenzen stoßen könnte – eine Datenbank hingegen ist darauf ausgelegt, große Mengen an Daten zur Speicherung und Verwaltung aufzunehmen. 

Mit einer Datenbank wäre der Grundstein für ein optisch aufgeräumtes, einfacher zu bedienendes und erweiterbares System gelegt. Jede Praxis hätte ihren eigenen Eintrag, in dem alle Daten auf übersichtliche Art dargestellt werden könnten. Zudem könnten sämtliche Dateien (wie eben die Vertragsunterlagen, Lebensläufe etc.), die bisher in einem Extra-Ordner auf SharePoint lagen und keine Verknüpfung zur Excel-Tabelle hatten, an entsprechender Stelle in der Datenbank abgelegt werden – somit wären alle Daten gebündelt an einem Ort verfügbar.

Ein weiterhin nicht unwichtiger Vorteil einer Datenbank gegenüber Excel ist, dass auch komplexere Abfragen möglich sind[3]. Mit den Formeln bei Excel lassen sich zwar auch viele Suchanfragen auslesen, jedoch ist hier zum einen sehr viel Expertise gefragt, zum anderen sind aufwendigere Abfragen einfach nicht machbar. Die Datenbank könnte hier Abhilfe schaffen, was in vielen Bereichen von Nutzen wäre – so zum Beispiel bei einer Abfrage, die aus allen teilnehmenden Praxen diejenigen selektiert, welche eine Mehrwertsteuerpflicht haben und zudem in einem bestimmten Zeitraum an Studie XY teilgenommen haben.

Mit dem Einsatz einer Datenbank ist insgesamt das Potential gegeben, auch in Zukunft mit den Anforderungen mitzuwachsen – seien es größere Datenmengen, aufwendigere Abfragen oder neue Funktionalitäten.

**4.	Fazit**

Zu den aktuellen datenintensiven Prozessen im Rahmen des GestDiab-Registers gehören das Forschungsdatenmanagement, das Management von kollaborativ genutzten Ordnern und Dateien sowie die Verwaltung der Teilnehmerdaten. Letzteres ist ein Bereich, der noch Optimierungspotential aufweist, daher wäre hier ein Umdenken im standardisierten Vorgehen empfehlenswert. Ein Umstieg von der Excel-Tabelle auf eine Datenbank hätte eine Reihe von Vorteilen wie zum Beispiel eine bessere Erweiterbarkeit, die Möglichkeit, größere Datenmengen zu speichern, komplexere Abfragen zu realisieren bzw. alles in allem, auf künftige Neuerungen wie ergänzende Funktionen und andere Weiterentwicklungen vorbereitet zu sein.

**Quellenverzeichnis:**

[1] Kindling, Maxi und Schirmbacher, Peter: „Die digitale Forschungswelt“ als Gegenstand der Forschung. Information – Wissenschaft – Praxis 64 (2013)

[2] https://www.forschungsdaten.info/themen/organisieren-und-aufbereiten/datenorganisation/ (Stand: 15.05.2021)

[3] https://www.bisnode.de/wissen/studien/kundendaten-nicht-in-excel-anlegen/ (Stand: 15.05.2021)
