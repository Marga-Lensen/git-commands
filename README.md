# Was ist Git?

![git and github](https://devmountain.com/wp-content/uploads/2022/01/Gitvs_Github-1a-1.jpg)

git ist ein Versionskontrollsystem für Entwickler, Autor oder Designer.

## Vorteile von Git:

1. Versionsverfolgung

2. Branches und Merging

3. Zusammenarbeit

## Voraussetzungen

1. Terminal
2. Texteditor
3. git provider (github, Bitbucket,GitLab )

![git provider](https://codefresh.io/docs/images/integrations/git/git-provider-menu.png)


### Installation

- Nach der Installation von Git überprüfen Sie es mit dem Befehl:


```
git --version

```

### Erstellen eines einfachen Projekts

1. im Terminal und navigieren Sie zu Ihrem gewünschten Projektverzeichnis.
2. Initialisieren Sie ein Git-Repository:

```
git init 
```
3. Erstellen Sie eine Textdatei (z. B. recipe.txt) und fügen Sie einige Aufgaben hinzu.

4. Stagen Sie Ihre Änderungen:
```
git add recipe.txt
```
5. Committen Sie Ihre Änderungen:

```
git commit -m "Erster Commit: recipe liste hinzugefügt"


```

6. 


```
git log


```



# Typische Git Befehle


| Befehl                               | Erklärung                                                                                |
|--------------------------------------|------------------------------------------------------------------------------------------|
| `$ git init`                         | Wenn wir diesen Befehl in einem order ausführen, erstellen wir hier ein neues Repository |
| `$ git status`                       | Zeigt uns den aktuellen Status eines Branches an, zb ob eine Datei verändert wurde       |
| `$ git add .`                        | fügt der Stage alle aktuellen veränderungen hinzu                                        |
| `$ git add [dateiname]`              | fügt der Stage spezifische Datein hinzu                                             |        
| `$ git rm [dateiname]`               | löscht eine spezifische Datei aus dem git repository                                     |
| `$ git commit -m "[nachricht]"`      | erstellt einen commit. Wichtig: erst adden, dann commiten, nachricht nicht vergessen     |
| `$ git push`                         | Ein repo von lokal auf github aktualisieren (hochschieben)                               |
| `$ git log`                          | gibt ein detailliertes log über alle commits des repos aus                               |
| `$ git log -p`                       | gibt ein detailliertes log mit allen änderungen der commits aus                          |
| `$ git log --pretty=oneline`         | gibt ein komprimiertes log mit ID und message des commits aus                            |
| `$ git revert [commit ID] --no-edit` | stellt einen früheren commit wieder her |
| `$ git fetch`                        | git fetch importiert Commits von einem Remote-Repository in das lokale Repo              |
| `$ git merge`                        | nach einem git fetch werden die Änderungen mit merge eingefügt
| `$ git pull`                         | ein repo auf github auf lokal aktualisieren (runterziehen) fetch + merge in einem Schritt) |
| `$ git clone [link von github]`      | ein repo local kopieren        | 
