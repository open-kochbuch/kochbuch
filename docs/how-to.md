# How To...

## 1. Wie ist dieses online Kochbuch aufgebaut? 
Das Kochbuch besteht aus einer Sammlung von Text Dateien, die zu einer Website zusammengestellt werden. Jedes Rezept ist eine Datei. Alle Rezepte sind in Markdown Syntax geschrieben. Markdown ist einfach eine simple Art von Textformattierung. [Hier](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) findest du eine Übersicht, wie diese Formattierung funktioniert. 

Falls du das Kochbuch nur anschauen möchtest, geht das ganz einfach über [https://noahedrich.github.io/kochbuch](https://noahedrich.github.io/kochbuch). Dort kannst du dich durch die Rezepte klicken wie bei jeder anderen Website. 

Wenn du selbst zu dem Kochbuch beitragen möchtest, kannst du dies ganz einfach in deinem Browser über [GitHub](https://github.com/) tun. Dafür wirst du einen GitHub account brauchen, dieser ist kostenlos. Einen account kannst du [hier](https://github.com/join?source=header-home) erstellen. Die weiteren Schritte werden im Folgenden erklärt. 

## 2. Wie kann ich ein Rezept hinzufügen? 

### Erstelle eine neue Datei
1. Logge dich auf [github.com](https://github.com/) ein. 
2. Gehe auf die [repository main page](https://github.com/noahedrich/kochbuch/) des Kochbuchs. 
3. In der Mitte der Seite siehst du eine Liste von Ordnern und Dateien. Klicke auf den `docs` Ordner. 
![Repo Main Page](https://noahedrich.github.io/kochbuch/bilder/howto_repomainpage.png)
4. Jetzt siehst du eine weitere Liste von Ordnern und Dateien. Suche jetzt den Ordner aus, wo du dein Rezept hinzufügen willst (z.B.: `Nachtisch`) und klicke darauf. 
5. In der Leiste über den Dateinamen, klich auf den Knopf "Create New File". 
![Create New File](https://noahedrich.github.io/kochbuch/bilder/howto_createnewfile.png)
6. Gib deiner neuen Datei einen Namen. Am Besten den Namen deines Rezepts. Benutze hier anstatt Leerzeichen den Bindestrich (`-`). Vergesse nicht am Ende die Dateierweiterung `.md` hinzuzufügen. 
   * Zum Beispiel, wenn du ein Puddingrezept hinzufügst, könntest du deine Datei `pudding.md` nennen. (Du musst natürlich einen Dateinamen benutzten der in dem Ordner noch nicht existiert.) 
7. In dem Hauptfeld kannst du das Rezept als Text hinzufügen. Du kannst (musst aber nicht!) [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) benutzen um deinen Text zu formattieren. 
8. Fertig? Dann klicke unten links auf den grünen Knopf "Commit new file". 
![Commit New File](https://noahedrich.github.io/kochbuch/bilder/howto_commitnew.png)
9. Nun wird dir wieder die Liste der Dateien in dem Ordner angezeigt. Klicke auf die Datei die du eben erstellt hast um den Inhalt anzusehen. 
10. Willst du noch etwas ändern? Klicke einfach oben rechts auf das Bleistiftsymbol. Wenn du fertig bist klicke den Knopf "Commit changes". 
![Make changes](https://noahedrich.github.io/kochbuch/bilder/howto_edit.png)

### Füge die Datei dem Inhaltsverzeichnis hinzu
Du hast deine Rezeptdatei erstellt? Super! Jetzt fehlt nur noch ein Schritt, damit dein Rezept auch leicht zu finden ist. 
1. Gehe wieder zu der [repository main page](https://github.com/noahedrich/kochbuch/) und klicke auf den `docs` Ordner. 
2. Klicke auf die Datei `index.md`. 
3. Klicke auf das Bleistiftsymbol oben rechts um die Datei zu bearbeiten. 
4. Füge deine eben erstellte Datei dem Inhaltsverzeichnis hinzu, in dem folgenden Format: 

```
## Nachtisch -> füge es unter dem Absatz hinzu der dem Ordner deiner Datei entspricht. 

* [Name des Rezeptes](ordnername/dateiname)
* [Der Beste Pudding der Welt](nachtisch/pudding) -> Beispiel deiner neuen Datei, vergiss nicht den Ordnernamen!
```
Das ist alles! Schau dir die Kochbuchwebsite an um dein neues Rezept zu begutachten (es kann einige Minuten dauern, bis die Änderungen zu sehen sind). 

## 3. Wie kann ich ein bestehendes Rezept ändern? 

1. Logge dich auf [github.com](https://github.com/) ein. 
2. Gehe auf die [repository main page](https://github.com/noahedrich/kochbuch/) des Kochbuchs.
3. Klicke auf den `docs` Ordner in der Liste der Dateien. 
4. Navigiere zu dem Ordner wo sich das Rezept befindet, dass du ändern willst und klicke auf die Datei des Rezepts. 
5. Klicke auf das Bleistiftsymbol oben rechts und bearbeite die Datei. 
6. Für eine Vorschau von wie die Datei mit Formattierung aussehen wird klicke oben links auf "Preview Changes". 
![Preview Changes](https://noahedrich.github.io/kochbuch/bilder/howto_preview.png)
7. Wenn du fertig bist klicke unten links auf "Commit changes". 

## Extra Tips 
### Bilder zu den Rezepten Hinzufügen 
(vergesse nicht datei typ )
