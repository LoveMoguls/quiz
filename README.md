# quiz

Färdiga quiz att dela med barnen som sms-länk.

## Namnregel

Varje quiz får en egen mapp: `barn-ämne-vVECKA`, med gemener och bindestreck och utan å, ä eller ö.

- `vanessa-biologi-v44`
- `bella-matte-v45`
- `charles-engelska-v46`

## Struktur

```
quiz/
├── index.html                  startsida (ingen länklista)
├── README.md
└── vanessa-biologi-v44/
    └── index.html              det färdiga quizet, en enda fil
```

Länken blir `https://lovemoguls.github.io/quiz/vanessa-biologi-v44/`.

## Regler

- Quizen byggs i det privata repot `quizmotor`. Hit kopieras bara den färdiga HTML-filen, döpt till `index.html`.
- Repot är publikt. Lägg aldrig betyg, svar från barnen eller andra personuppgifter här.
