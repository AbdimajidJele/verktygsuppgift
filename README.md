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