# GitHub-Pages-Update für pluennen_chaos_naht

Dieses Paket aktualisiert die Hauptillustration: Die Seite erwartet jetzt ein Bild mit dem exakten Dateinamen `hermine.jpg` im obersten Verzeichnis deines GitHub-Repositorys.

## Wenn die Website bereits online ist

1. Öffne dein GitHub-Repository.
2. Lade deine Bilddatei hoch und nenne sie exakt `hermine.jpg` (alles kleingeschrieben). Lege sie direkt ins oberste Verzeichnis des Repositorys – dort, wo `index.html` liegt, **nicht** in `assets`.
3. Ersetze im Ordner `assets` die vorhandene Datei `app.js` durch die Datei `assets/app.js` aus diesem Paket.
4. Warte kurz auf GitHub Pages und lade die Website neu. Falls du noch die alte Version siehst, erzwinge ein Neuladen: Windows/Linux `Ctrl+F5`, Mac `Cmd+Shift+R`.

Die HTML-Datei ruft das JavaScript über den relativen Pfad `./assets/app.js` auf. Du musst `index.html` und `assets/styles.css` normalerweise nicht ändern. `./hermine.jpg` ist absichtlich relativ statt `/hermine.jpg`, damit das Bild auch auf einer GitHub-Pages-Projektadresse mit Repository-Unterpfad gefunden wird.

## Paketinhalt

- `index.html` – Hauptdatei, exakt so benannt.
- `assets/app.js` – aktualisiertes Website-Bundle mit `./hermine.jpg`.
- `assets/styles.css` – Website-Stile.
- `README.md` – diese Anleitung.

Das Bild `hermine.jpg` wird nicht mitgeliefert: Verwende deine eigene JPG-Datei und lade sie selbst ins Repository-Hauptverzeichnis hoch.
