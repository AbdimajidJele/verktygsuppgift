# Verktygsuppgift

Det här är en övning där jag lär mig grundläggande terminalkommandon. Syftet med övningen var att öva på att navigera i filsystemet, skapa mappar/filer, och koppla ihop terminalen med VS Code. De moment som jag gjorde var att skapa en kurs-projektmapp, skapa en textfil och öppna VS Code. Har lärt mig nu även hur mkdir, touch, cd fungerar i praktiken.

## Git-kommandon

- git init, skapar ett nytt Git-repository i mappen du står i. Jag använde den för att göra min projektmapp verktygsuppgift till ett Git-repository, så att Git kan börja spåra ändringar.

- git status, visar en lista över vilka filer som är ändrade, nya, eller redan sparade (committade). Bra för att "dubbelkolla" innan man gör något. Jag körde precis git status och den visade mig att README.md är modified samt min fil mina-bash-kommandon.txt.

- git commit -m "meddelande", sparar en ny version i historiken av de filer du lagt till med git add. Meddelandet beskriver vad som ändrats. Jag använde git commit -m "first commit" för att spara min första version.

- git push, skickar upp min lokala commits till GitHub servern, så att de syns där online. Jag använde git push -u origin main för att ladda upp min kod för första gången (-u kopplar ihop min lokala branch med main på GitHub, så jag bara kan skriva git push nästa gång).

- git add, förbereder filändringar inför nästa commit, s.k. "staging" - Git sparar inget automatiskt, man måste välja vad som ska vara med. Jag använde git add README.md för att förbereda min README-fil inför commit.

- git branch, hanterar branches, dvs parallella "spår" av koden. Jag använde git branch -M main för att döpa om min huvudbranch till main.

- git remote, kopplar min lokala mapp till ett repository på en server, t.ex. GitHub. Jag använde git remote add origin <url> för att koppla min lokala mapp till repot jag skapade på GitHub.

## Vad är ett repository, en commit och en versionshistorik?

Ett repository är själva "projektet" ur Gits perspektiv - en mapp där Git håller reda på alla filer och all historik av ändringar. Finns på en server i GitHub som man kan dela med andra samt lokalt i din dator.

Commit däremot är en "sparad version" av dina filer vid en tidpunkt. Varje commit har ett meddelande som beskriver vad som ändrades. Tänk på det som ett foto av hur projektet såg ut just då, man kan alltid gå tillbaka och titta på ett tidigare foto.

Versionshistorik är den samlade listan av alla commits som man har gjort i tidsordning - hela "livshistorien" för självaste projektet. Genom historiken kan man se hur koden vuxit fram, vem som gjort vad samt när.