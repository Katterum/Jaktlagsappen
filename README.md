# Jaktlag 1.1 Premium

Mobilanpassad testversion som kan köras direkt med GitHub Pages. Ingen byggkedja krävs.

## Publicera på GitHub Pages
1. Skapa ett nytt GitHub-repository.
2. Ladda upp alla filer och mappar i detta paket till repositoryts rot.
3. Öppna Settings > Pages.
4. Välj Deploy from a branch, branch `main` och mappen `/ (root)`.
5. Öppna länken som visas av GitHub Pages.

## Funktioner i prototypen
- Poängmodell eller kalv/kid som procent av vuxen.
- Separata värden för Dov, Älg och Kron.
- Medlem eller extern skytt.
- Mottagare, markandel, kontaktuppgifter och statistik.
- Grafisk resultatsammanställning.
- Lokal bokning av sex områden.
- Offline-cache och möjlighet att installera som PWA.
- Lokal JSON-säkerhetskopia.

## Viktigt före verklig användning
All data sparas endast i webbläsarens localStorage. Det finns ingen inloggning, central databas eller synkronisering mellan mobiler. Kartbilden är en användartillhandahållen referensbild och områdesmarkörerna är bara ett visuellt koncept. För en riktig kartfunktion bör markgränser och pass importeras som koordinater/KML och visas via en karttjänst med korrekt licens/API-nyckel. Publicera inte kontaktuppgifter, exakta jaktplatser eller annan känslig information i ett publikt repository.
