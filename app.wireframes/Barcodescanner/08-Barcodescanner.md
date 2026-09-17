# 08 — Barcodescanner

## Wireframe
```text
┌─────────────────────────────┐
│ ← Barcode scannen           │
│                             │
│                             │
│      ┌───────────────┐      │
│      │               │      │
│      │    SCAN       │      │
│      │               │      │
│      └───────────────┘      │
│                             │
│ Richt de camera op          │
│ de barcode                  │
│                             │
│ [ Handmatig zoeken ]        │
└─────────────────────────────┘

             ↓

┌─────────────────────────────┐
│ Product gevonden ✓          │
│                             │
│ Protein Bar                 │
│                             │
│ 210 kcal                    │
│ 20g protein                 │
│ 18g carbs                   │
│ 7g fat                      │
│                             │
│ Portie [ 1 ]                │
│                             │
│ [ Toevoegen aan dagboek ]   │
└─────────────────────────────┘
```

## Styling
- Camera preview fullscreen
- Scanframe gecentreerd
- Korte instructie
- Resultaat als card/bottom sheet
- Grote confirm CTA
- Duidelijke loading/error states

## Must-have
- Camera/scanner
- Barcode detectie
- Product zoeken
- Productgegevens
- Calorieën/macros
- Portiegrootte
- Toevoegen aan dagboek
- Foutmelding bij onbekend product
- Handmatige zoekfallback

## Could-have
- Recent gescande producten
- Favorieten
- Eigen producten
- Meerdere producten scannen
- AI-herkenning
- Productvergelijking
- Voedingsadvies
