![Header Image](images/header.jpg)  

# Therapie-Kontakte in deiner Nähe

Bis zu 100 Kontakte von 116117 als Excel-Download – mit einfacher Anrufliste. Spart dir Zeit und Nerven.
Ein einfacher 116117 Psychotherapie Suche Exporter zur Unterstützung bei der Suche nach Psychotherapieplätzen in Deutschland.

## Live-App

<p align="left">
  <a href="https://116117-psychotherapie-suche-exporter.streamlit.app/" target="_blank">
    <img src="https://img.shields.io/badge/%20Zur%20Live--App-Starten-blue?style=for-the-badge&logo=streamlit" 
         alt="Live App" 
         height="50">
  </a>
</p>

## ⚡ Update (Dezember 2025 - 116117 blockt API calls):
Der (inoffizielle) Endpoint https://arztsuche.116117.de/api/data erfordert inzwischen eine gültige Browser-Session (u.a. JSESSIONID + Cookies). Direkte Python-Requests liefern daher HTTP 500 (leer). Ein automatisches „Nachbauen“ der Browser-Session zur weiteren API-Nutzung ist mir rechtlich zu heikel. Da das offizielle Entwicklungsteam an einem ähnlichen offiziellen Feature arbeitet, werde ich diese App nicht weiterentwickeln.

## ⚡ Update (Oktober 2025):
Nach direktem Austausch mit dem offiziellen Entwicklungsteam der 116117-App wurde bestätigt, dass das vorgeschlagenes Feature in den offiziellen Entwicklungszyklus aufgenommen wird. 🎉
Die Weiterentwicklung dieser App ist damit eingestellt, da die Funktion künftig direkt in der offiziellen 116117-Arztsuche integriert wird.
Ein genauer Zeitplan wurde von 116117 nicht kommuniziert.


## Hintergrund

Ich habe diese App entwickelt, weil es extrem schwierig ist, freie gesetzliche Therapieplätze zu finden. Oft muss man zahlreiche Praxen kontaktieren, nur um immer wieder zu hören, dass keine Kapazitäten frei sind. Dieses Problem ist systemisch – und wer nachweislich keinen Platz findet, hat unter Umständen Anspruch auf Kostenerstattung durch die Krankenkasse wegen Systemversagen. Diese App soll helfen, schneller und einfacher dokumentiert nach verfügbaren Angeboten zu suchen. Zudem kann ein Export der Arztsuche als Datei sehbehinderten Personen helfen, wie in diesem [FragDenStaat-Post](https://fragdenstaat.de/a/299392) angefragt.


## Funktionen

- Suche nach Therapeut:innen in deiner Nähe anhand deiner Postleitzahl  
- Filter nach Verfahrensart, Setting, Einzel/Gruppentherapie
- Exportiere Ergebnisse inkl. Adresse, Fachrichtung und Telefonnummer  
- Telefonzeiten werden strukturiert abgespeichert in separatem Tab
- Telefonzeiten momentan sowie die nächsten fünf Telefonzeiten werden direkt angezeigt


## Beispiel Exporte

Die folgenden Dateien zeigen, welche Daten über die App exportiert werden können:

- ![Beispiel Export Praxisdaten](images/beispiel_export_praxisdaten.png)  
  Beispiel für die exportierten Praxisdaten (Adresse, Fachrichtung, Telefonnummer).

- ![Beispiel Export Telefonsprechzeiten](images/beispiel_export_telefonsprechzeiten.png)  
  Beispiel für die exportierten Telefonsprechzeiten.

- [Beispiel Template Excel](images/Beispiel%20Template.xlsx)  
  Beispiel einer Excel-Datei, in der die Suchergebnisse exportiert werden können.


## Nutzung der 116117 API

Dies ist ein nicht-kommerzielles Projekt. Es besteht keine Verbindung zur KBV oder 116117. Alle Daten stammen aus öffentlich zugänglichen Quellen von 116117.de - über die API von [116117.de](https://arztsuche.116117.de/) abgerufen. Es ist wichtig, mit der Nutzung dieser API vorsichtig umzugehen, um Missbrauch und übermäßige Anfragen zu vermeiden. Das API-Angebot ist nicht für den intensiven, automatisierten Abruf von großen Datenmengen gedacht. Bitte stelle sicher, dass deine Nutzung der API den rechtlichen Bestimmungen entspricht und keine negativen Auswirkungen auf die Verfügbarkeit der API für andere Nutzer:innen hat.


## Mitwirkende
@flandweber - Danke für die Unterstützung bei der Automatisierung der API-Header!

@LeaRain - Toller Vortrag auf der EasterHegg 2025 zu dem Thema: https://media.ccc.de/v/eh22-107-psychotherapiesuche-erfahrungsbericht-mit-automatisierung/playlist


## Lizenz

Dieses Projekt steht unter der **MIT-Lizenz**.

Diese App verwendet Daten aus dem Repository [WZBSocialScienceCenter/plz_geocoord](https://github.com/WZBSocialScienceCenter/plz_geocoord), das unter der **Apache License 2.0** lizenziert ist. Weitere Informationen unter: http://www.apache.org/licenses/

