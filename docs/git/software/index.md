# Git Software Tools

In dit hoofdstuk bespreken we een aantal populaire tools die het werken met Git eenvoudiger maken. 
Naast de command-line interface (`git bash`) bestaan er namelijk heel wat grafische toepassingen 
die een visuele laag leggen bovenop Git.

---

## Git Bash

Git Bash is de standaard command-line omgeving die meegeleverd wordt met Git op Windows.

### Installatie
1. Ga naar [https://git-scm.com/downloads](https://git-scm.com/downloads).
2. Kies de versie voor **Windows** en installeer.
3. Tijdens installatie kan je **Git Bash** mee installeren.
4. Na installatie kan je in Windows zoeken naar *Git Bash* en het programma openen.

[@TODO IMAGE: Screenshot van Git Bash venster]

### Eerste stappen in Git Bash
```bash
# Maak een nieuwe map en ga ernaartoe
mkdir mijn-project
cd mijn-project

# Maak een lege Git repository
git init

# Maak een bestand en voeg toe
echo "Hello Git" > hello.txt
git add hello.txt

# Commit het bestand
git commit -m "Eerste commit"

# Controleer status
git status
```

!!! tip "Waarom Git Bash leren?"
    De command-line is de basis van Git. Als je begrijpt wat hier gebeurt, 
    begrijp je ook wat de GUI-tools onder de motorkap doen.

---

## GitHub Desktop

GitHub Desktop is een gratis GUI-tool van GitHub zelf.  
Het richt zich vooral op eenvoud en gebruiksvriendelijkheid.

### Installatie
1. Ga naar [https://desktop.github.com/](https://desktop.github.com/).
2. Download en installeer de toepassing.
3. Log in met je **GitHub account**.

[@TODO IMAGE: Screenshot installatie GitHub Desktop]

### Eerste workflow
1. **Clone een repository** vanuit GitHub.
2. Maak een nieuwe file of wijzig een bestaande.
3. Je ziet de wijzigingen in het **Changes** venster.
4. Vul een commit message in en klik op **Commit to main**.
5. Klik daarna op **Push origin** om je wijzigingen online te zetten.

[@TODO IMAGE: Screenshot workflow in GitHub Desktop]

!!! example "Scenario"
    Je werkt aan een schoolproject en wil samen met je team werken.  
    - Clone het project vanuit GitHub.  
    - Werk lokaal, commit en push.  
    - Je teamgenoten kunnen nadien je wijzigingen pullen.  

---

## GitKraken

GitKraken is een krachtige, visuele Git-client. Studenten kunnen vaak gratis gebruik maken van de Pro-versie.

### Installatie
1. Ga naar [https://www.gitkraken.com/](https://www.gitkraken.com/).
2. Download de juiste versie (Windows, Mac, Linux).
3. Log in met je GitHub account (of via GitLab/Bitbucket).

[@TODO IMAGE: Screenshot GitKraken login]

### Eerste workflow in GitKraken
1. **Clone een repository** via de GUI (gebruik GitHub login of repo-URL).
2. Maak een nieuwe branch in de linkerkantlijn.
3. Pas een bestand aan en klik op **Stage file**.
4. Voeg een commit message toe en klik op **Commit changes**.
5. Klik op **Push** om de branch online te zetten.

[@TODO IMAGE: GitKraken branches en commits]

!!! tip "Voordelen van GitKraken"
    - Sterke visuele weergave van branches en merges.
    - Drag-and-drop om te mergen of rebasen.
    - Handig in grotere teams met veel parallel werk.

---

## Best Practices

- Leer eerst de **basis in Git Bash** → zo begrijp je echt wat er gebeurt.  
- Gebruik **GitHub Desktop** als je snel en eenvoudig wil werken, zeker in kleinere projecten.  
- Gebruik **GitKraken** bij grotere projecten waar overzicht en visualisatie cruciaal zijn.  
- Vermijd afhankelijkheid van enkel GUI-tools: je moet steeds ook de command-line begrijpen.  



---

## Oefeningen

1. **Git Bash**:  
   - Maak een nieuwe repo en doe minstens 3 commits.  
   - Bekijk de commit history met `git log --oneline`.  

2. **GitHub Desktop**:  
   - Clone een GitHub repo.  
   - Voeg een bestand toe, commit en push het.  

3. **GitKraken**:  
   - Maak een nieuwe branch.  
   - Doe een commit in deze branch en merge hem terug in `main`.  

!!! tip
    Oefen elk van deze stappen meermaals zodat je vertrouwd geraakt met de workflow.
