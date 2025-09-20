# Git Basics

Git is een **gedistribueerd versiebeheersysteem** dat ontwikkeld werd door Linus Torvalds in 2005.  
Het helpt ontwikkelaars om samen te werken aan code, wijzigingen bij te houden en oudere versies te herstellen.

## Waarom Git?

- **Samenwerken**: meerdere ontwikkelaars kunnen parallel werken.  
- **Versiegeschiedenis**: elke wijziging wordt bewaard, je kan terug in de tijd.  
- **Betrouwbaar**: Git is ontworpen voor grote projecten (zoals Linux).  
- **Snel**: Git werkt grotendeels lokaal, waardoor commando’s zeer performant zijn.  

[@TODO IMAGE: Schema met lokale repo en remote GitHub repo]

!!! note
    Zonder kennis van Git ben je vandaag “niemand” in de IT-sector. Vrijwel elke vacature vraagt ervaring met versiebeheer.

## Belangrijkste concepten

- **Repository (repo)**: map waarin Git alle versies van bestanden bewaart.  
- **Commit**: een momentopname van je project.  
- **Branch**: een alternatieve tak van ontwikkeling.  
- **Remote**: een versie van je repo op een server (bv. GitHub).  

## Voorbeeld workflow

```bash
# Nieuwe repo maken
git init

# Bestand toevoegen
echo "Hello Git" > hello.txt
git add hello.txt

# Commit maken
git commit -m "Eerste commit"

# Status bekijken
git status
```

---

## Oefeningen

1. Maak een map `git-basics-demo` en initialiseer een repository.  
2. Voeg een bestand `readme.md` toe en commit dit.  
3. Pas het bestand aan en maak een tweede commit.  
4. Bekijk de geschiedenis met:  

   ```bash
   git log --oneline
   ```
