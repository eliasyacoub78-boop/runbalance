# RunBalance – mobil PWA

## Funktioner
- Mobilanpassad översikt och försiktigt återstartsprogram
- Träningsdagbok med distans, tid, knärespons och dagsform
- Återhämtningslogg för knä, energi, sömn och ömhet
- Lokal lagring i webbläsaren samt export av logg som JSON
- PWA-manifest, hemskärmsikon och enkel offline-cache

## Publicera
Den här mappen behöver läggas på ett webbhotell som stöder statiska filer och HTTPS (t.ex. GitHub Pages, Netlify eller motsvarande). Ladda upp samtliga filer och mappar utan att ändra relativa sökvägar. Efter publicering öppnar du HTTPS-adressen i Safari på iPhone.

## Installera på iPhone
1. Öppna den publicerade HTTPS-adressen i Safari.
2. Tryck på Dela.
3. Välj Lägg till på hemskärmen.
4. Slå på "Öppna som webbapp" om alternativet visas.
5. Tryck på Lägg till.

## Viktiga begränsningar
- Detta är en lokal prototyp, inte en App Store-app.
- Loggar sparas på den aktuella enheten/webbläsaren. De synkas inte mellan enheter och kan försvinna om webbplatsdata rensas. Exportera loggen regelbundet.
- Ingen automatisk Strava-import eller Strava OAuth är implementerad.
- Inget konto, molnbackup eller automatisk coachning finns i denna första version.
- Det finns ingen medicinsk diagnos; planen är försiktig och bör anpassas efter symtom och vid behov fysioterapeutisk rådgivning.
