# 🏛️ Simrishamn

Saker relaterade till Simrishamn kommun - utbildningsmaterial och dokumentation.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://lundgren9.github.io/Simrishamn/)

---

## 📁 Innehåll

### 📚 Program och verktyg

| Mapp | Beskrivning | Länk |
|------|-------------|------|
| **1/** | Felsökningsrapport: Raindance (18 jan 2026) | [Besök →](https://lundgren9.github.io/Simrishamn/1/) |
| **2/** | Avstämning mellan konto 2880 och 2881 | [Besök →](https://lundgren9.github.io/Simrishamn/2/) |

### 📖 Dokumentation

| Fil | Beskrivning | Länkar |
|-----|-------------|--------|
| **GitHub.html** | Guide för Git & GitHub - synkronisering lokalt ↔ remote | [📄 Visa sida](https://lundgren9.github.io/Simrishamn/GitHub.html) · [💻 Källkod](https://github.com/lundgren9/Simrishamn/blob/main/GitHub.html) |

> **Skillnad:** "Visa sida" öppnar den färdiga webbsidan med styling. "Källkod" visar HTML-koden på GitHub.

---

## 🔧 Hur använda detta repository

### Klona till din dator

```powershell
# Navigera till önskad mapp
cd "D:\Din\Mapp"

# Klona repot (skapar undermapp "Simrishamn")
git clone https://github.com/lundgren9/Simrishamn.git

# ELLER klona direkt till nuvarande mapp (mappen måste vara tom!)
git clone https://github.com/lundgren9/Simrishamn.git .
```

### Dagligt arbetsflöde

```powershell
# Hämta senaste ändringarna
git pull origin main

# Efter ändringar - lägg till, committa och pusha
git add .
git commit -m "Beskrivning av ändringarna"
git push origin main
```

> **💡 Tips:** Se [Git-synkroniseringsguiden](https://lundgren9.github.io/Simrishamn/GitHub.html) för komplett guide!

---

## 📂 Mappstruktur

```
Simrishamn/
├── README.md              # Denna fil
├── GitHub.html            # Git-synkroniseringsguide
├── du_har_inte_tillstand.jpg
├── 1/                     # Raindance-felsökning
│   ├── README.md
│   └── index.html
└── 2/                     # Avstämning balanskonton
    ├── README.md
    └── index.html
```

---

## 🌐 Publicerat på GitHub Pages

Alla HTML-filer är tillgängliga online via GitHub Pages:

- **Huvudsida:** https://lundgren9.github.io/Simrishamn/
- **Program 1:** https://lundgren9.github.io/Simrishamn/1/
- **Program 2:** https://lundgren9.github.io/Simrishamn/2/

---

## 💻 Teknisk information

- **Språk:** HTML, CSS, JavaScript (vanilla)
- **Hosting:** GitHub Pages
- **Senast uppdaterad:** 18 januari 2026

---

## 📝 Hur skapa nya kataloger i GitHub

### Via GitHub (webben)
1. Gå till https://github.com/lundgren9/Simrishamn
2. Klicka **Add file** → **Create new file**
3. I filnamnsfältet skriv `3/index.html` (skapar katalogen "3" med en index.html-fil)
4. Fyll i HTML-innehåll och commit-meddelande
5. Klicka **Commit new file**

### Via Git lokalt
```powershell
# Skapa ny mapp med index.html
mkdir 3
New-Item -Path "3/index.html" -ItemType File

# Lägg till och committa
git add .
git commit -m "Skapar mapp 3 med index.html"
git push origin main
```

---

### ❓ Varför inte `.gitkeep`?

Du kanske har sett att man ibland skapar `3/.gitkeep` istället. Här är förklaringen:

| Fil | Vad det är | När använda |
|-----|------------|-------------|
| **`index.html`** | En riktig HTML-fil som blir en webbsida | ✅ **Rekommenderas!** Om mappen ska innehålla en webbsida |
| **`.gitkeep`** | En tom "dummy-fil" utan innehåll | Endast om mappen ska vara tom (ingen webbsida) |

> **Viktigt att veta:** Git kan inte spåra tomma mappar! Därför måste det finnas minst en fil i mappen. `.gitkeep` är bara ett påhittat namn som utvecklare använder som "placeholder" – det är ingen speciell Git-funktion. Du kan lika gärna använda `README.md` eller `index.html`.

**Slutsats:** Använd `3/index.html` direkt – det är enklare och mer användbart!

---

## 👤 Kontakt

Repository ägs av **lundgren9**.

