# Git Commands:
// Just a Cheatcheet for Git Commands to learn them.
___
### Initialisiere ein neues Git Repository

```bash
git init
```
### Zeigt den Status des Git Repositorys an (veränderte Dateien etc.)

```bash
git status
```
### fügt (staged) eine Datei zu einem Commit (hochladen) hinzu.

```bash
git add index.html
```

### fügt (staged) alle Dateien zu einem Commit hinzu.

```bash
git add .
```

### -m steht für Message und in die "" kommt eine Beschreibung von den Code Veränderungen rein.

```bash
git commit -m "Commit message"
```

### hochladen der commiteten dateien

```bash
git push
```

### zeigt vergangene Commits mit Hash, Autor des Commits, Zeitstempel und Beschreibung.

```bash
git log
```
  
### damit kann man zu anderen Commits zurückreisen. Basicly Back to the Future Commit.

```bash
git checkout <commit-hash>
```
 
### listet alle Banches auf und zeigt auch auf welchem Branch man gerade ist.

```bash
git branch
```
  
### erstelle eine andere Zeitline um andere dinge auszuprobieren die nicht auf dem Master-Branch passieren sollen. 

```bash
git branch <new-branch-name>
```
 
### damit kann man zu anderen Zeitlinien (Branches) reisen.

```bash
git checkout <branch-name>
```

### wenn ich test-branch zu master-branch mergen möchte, muss ich in die master-branch Timeline checkout machen wo ich hin mergen will und dann git merge test-branch machen. 

```bash
git merge <branch-name>
```
