# Branch Workflows

## Git Flow

Een populaire strategie:  
- `main` = stabiele code  
- `develop` = integratiebranch  
- `feature/*` = nieuwe functies  
- `hotfix/*` = snelle fixes

```mermaid
gitGraph
  commit id:"start"
  branch develop
  branch featureA
  commit
  checkout develop
  merge featureA
  checkout main
  merge develop
```

---

## Oefeningen

1. Simuleer Git Flow met een klein project.  
2. Maak een feature branch, commit, en merge terug in develop.  
3. Release naar main.
