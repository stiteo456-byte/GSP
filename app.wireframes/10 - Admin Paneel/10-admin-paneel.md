# 10 — Admin paneel

## Wireframe
```text
┌──────────────────────────────────┐
│ ←  Admin paneel             ⋮    │
│                                  │
│ Overzicht  Oefeningen  Gebruikers│
│ ──────────────────────────────── │
│                                  │
│ Oefeningen                       │
│ [ Zoek oefening...          🔍 ]  │
│                                  │
│ [+ OEFENING TOEVOEGEN]           │
│                                  │
│ ┌──────────────────────────────┐ │
│ │ Bench press                  │ │
│ │ Borst • Barbell              │ │
│ │                        [⋮]   │ │
│ ├──────────────────────────────┤ │
│ │ Goblet squat                 │ │
│ │ Benen • Dumbbell             │ │
│ │                        [⋮]   │ │
│ ├──────────────────────────────┤ │
│ │ Pull-up                      │ │
│ │ Rug • Eigen lichaamsgewicht  │ │
│ │                        [⋮]   │ │
│ └──────────────────────────────┘ │
│                                  │
│ Gebruikers (24)                  │
│ [ Zoek gebruiker...         🔍 ]  │
│ ┌──────────────────────────────┐ │
│ │ Alex Jansen                  │ │
│ │ alex@email.nl • Actief       │ │
│ │                        [⋮]   │ │
│ └──────────────────────────────┘ │
│                                  │
│ Dashboard  Oefeningen  Profiel   │
└──────────────────────────────────┘
```

## Oefening toevoegen / wijzigen
```text
┌──────────────────────────────────┐
│ ←  Nieuwe oefening               │
│                                  │
│ Naam *                           │
│ [______________________________] │
│                                  │
│ Spiergroep *                     │
│ [ Kies spiergroep            ▾ ]  │
│                                  │
│ Materiaal                        │
│ [ Kies materiaal              ▾ ] │
│                                  │
│ Beschrijving                     │
│ [______________________________] │
│ [______________________________] │
│                                  │
│ [ ANNULEREN ]  [ OPSLAAN ]       │
└──────────────────────────────────┘
```

## Actiemenu oefening
- Wijzigen: opent hetzelfde formulier met de bestaande gegevens.
- Verwijderen: toont eerst een bevestigingsvenster met de naam van de oefening.
- Verwijderen kan pas definitief na een expliciete bevestiging.
- Bij verwijderen van een gebruikte oefening verschijnt een waarschuwing dat historische workouts behouden blijven.

## Gebruiker verwijderen
```text
┌──────────────────────────────────┐
│ Gebruiker verwijderen?           │
│                                  │
│ Alex Jansen                      │
│ alex@email.nl                    │
│                                  │
│ Dit verwijdert het account en    │
│ alle persoonlijke gegevens.      │
│ Deze actie kan niet ongedaan     │
│ worden gemaakt.                  │
│                                  │
│ [ ANNULEREN ] [ DEFINITIEF       │
│                 VERWIJDEREN ]   │
└──────────────────────────────────┘
```

## Styling
- Adminpaneel is duidelijk gescheiden van de gewone gebruikersnavigatie.
- Tabs maken het onderscheid tussen oefeningen en gebruikers zichtbaar.
- Elke rij toont naam, categorie en een compact actiemenu.
- De primaire CTA is `Oefening toevoegen`.
- Destructieve acties gebruiken een rode accentkleur en altijd een bevestigingsvenster.
- Formuliervelden hebben duidelijke labels en verplichte velden zijn gemarkeerd met `*`.
- Succes- en foutmeldingen verschijnen na opslaan of verwijderen.

## Must-have
- Overzicht van oefeningen
- Oefening toevoegen
- Oefening wijzigen
- Oefening verwijderen
- Gebruikers zoeken en bekijken
- Gebruiker verwijderen
- Bevestiging voor destructieve acties
- Validatie van verplichte velden
- Succes- en foutmelding
 goon
## Could-have
- Oefeningen filteren op spiergroep en materiaal
- Oefeningen archiveren in plaats van verwijderen
- Gebruikers blokkeren of reactiveren
- Activiteitenlogboek voor adminacties
- Paginering bij veel oefeningen of gebruikers
