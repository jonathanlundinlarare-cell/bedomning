# SO Bedömningsmall – Lokalt program

## Starta programmet (utan terminal)

### Windows
1. Installera Node.js från https://nodejs.org (engångssteg)
2. Dubbelklicka på:  **Starta SO Bedömning (Windows).bat**
   → Första gången tar det 1–2 minuter att installera, sen startar det direkt.

### Mac
1. Installera Node.js från https://nodejs.org (engångssteg)
2. Dubbelklicka på:  **Starta SO Bedömning (Mac).command**
   → Om Mac frågar om säkerhet: Ctrl+klicka → Öppna → Öppna
   → Första gången tar det 1–2 minuter att installera, sen startar det direkt.

---

## Var sparas datan?

- **Windows:** `Dokument\SO-Bedomning\data.json`
- **Mac:**     `Dokument/SO-Bedomning/data.json`

Kopiera data.json som säkerhetskopia när du vill.

---

## Filer i mappen

```
so-app/
├── Starta SO Bedömning (Windows).bat   ← Dubbelklicka (Windows)
├── Starta SO Bedömning (Mac).command   ← Dubbelklicka (Mac)
├── main.js       ← Programkod
├── preload.js    ← Programkod
├── index.html    ← Hela applikationen
├── package.json  ← Konfiguration
└── assets/       ← Ikon
```

---

*Obs: Node.js behöver bara installeras en gång. Programmet startar sedan med ett dubbelklick.*
