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

| Fil | Beskrivning |
|-----|-------------|
| [GitHub.html](GitHub.html) | Guide för Git & GitHub - synkronisering lokalt ↔ remote |

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

> **💡 Tips:** Se [GitHub.html](GitHub.html) för komplett guide om Git-synkronisering!

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
3. I filnamnsfältet skriv `3/.gitkeep` (skapar katalogen "3" med placeholder-fil)
4. Fyll i commit-meddelande och klicka **Commit new file**

### Via Git lokalt
```powershell
# Skapa ny mapp med placeholder
mkdir 3
New-Item -Path "3/.gitkeep" -ItemType File

# Lägg till och committa
git add .
git commit -m "Skapar mapp 3"
git push origin main
```

> **OBS:** Tomma mappar syns inte i Git - använd alltid placeholder-filer som `.gitkeep` eller `README.md`.

---

## 👤 Kontakt

Repository ägs av **lundgren9**.

