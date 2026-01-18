# Simrishamn
Saker relaterade till Simrishamn kommun

[Besök sidan: Felsökningsrapport: Raindance - den 18 januari 2026](https://lundgren9.github.io/Simrishamn/1/)

# Hur skapa kataloger i GitHub
## GitHub
Metod: Direkt i GitHub (webben) — för en eller ett fåtal kataloger
Gå till https://github.com/lundgren9/Simrishamn
Klicka "Add file" → "Create new file"
I fältet för filnamn skriv "1/.gitkeep" (det skapar katalogen "1" och filen .gitkeep)
Fyll i commit‑meddelande och klicka "Commit new file"
Upprepa för "2/.gitkeep", osv.

Tomma mappar syns inte i git — använd placeholder-filer (.gitkeep, README.md).
Kontrollera vilken branch du jobbar på: git branch --show-current. Om ni arbetar i en skyddad branch (main) kan det vara bättre att skapa en feature-branch: git checkout -b add-numbered-folders [...]
Katalognamn bestående av endast siffror är helt okej.
