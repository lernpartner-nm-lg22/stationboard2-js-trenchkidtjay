# Stationboard

## Vanilla JS
in app.js
1) für input und button JS element erstellen (querySelector/getElementById)
2) getData erstellen
3) displayData erstellen:

Was|Wie
--|--
Element finden| `document.querySelector()`
Inhalt ändern|`element.textContent = 'neuer Inhalt'`;
Input wert lesen|`inputElement.value`
Erreignis auswerten|`element.addEventListener(event, handler);`
Zeitobject umwandeln|`const timeString = time.toLocaleTimeString('de-CH');`
Tabelle reihe hinzufügen| `const row = tabelle.insertRow();`
Spalltenelement hinzufügen| `const cell = row.insertCell(0);`
|| folgendes funktioniert nur in `async` Function
API-Befehl auslösen|`const response = await fetch(url);`
API-Resultat lesen|`const data = await response.json();`
