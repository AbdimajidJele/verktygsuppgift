## Gemensamt repository i ett utvecklingsteam

Ett gemensamt repository fungerar som en central plats där alla i teamet kan hämta samma kodbas (git pull) eftersom alla har tillgång till den. Istället för att alla har sin egen separata version, synkar man mot samma källa så alla jobbar mot samma mål. 

Varje commit sparas med ett meddelande, vem som gjort en särskild ändring och när. Detta bidrar med att gruppen kan gå tillbaka och se exakt vad som ändrats över tid, av vem, samt varför. Om det uppstår ett särskilt problem kan man leta i historiken för att hitta vilken ändring som orsakade problemet.

Med branches kan varje person jobba på sin egen gren av koden - t.ex, en ny funktion - utan att påverka huvudkoden (main) förrän de är klara. När de är nöjda med resultatet slår de ihop sina ändringar i main. Så flera kan jobba parallellt utan att behöva störa varandra. 

Om man delade kod via mejl eller USB skulle man snabbt få krockande versioner, dvs man vet inte vem som har den senaste versionen. Man vet inte om flera personer har skrivit i samma fil samtidigt. Git löser detta genom att slå ihop ändringar och visa konflikter tydligt när de uppstår, istället för att filer bara dubblas eller skrivs över.