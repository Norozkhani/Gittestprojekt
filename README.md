# Vad jag lärt mig och andvänt mig med i terminalen gällande projekt skapande, navigering och git

### Detta är en mix av kommandon jag lärt mig under föreläsning, kunnat på egen hand sedan tidigare och som jag lärt mig genom egen research.

- **Terminalen**

  - PWD - se vart jag är (min path)

  - LS - Se vad som finns i den mappen/filen jag är inne i

  - CD filnamn - gå till/djupare in i mappar/filer

  - CD filnamn/filnamn/filnamn - gå ännu djupare i mappar/filer så man slipper gå 1 åt taget

  - ../ - backa ett steg

  - mkdir - Skapa ny mapp

  - echo "" filnamn.txt - skapa ny fil utan innehåll

  - echo "string" filnamn.txt - skapa en fil med text i

  - rmdir -d filnamn - ta bort fil

  - code . - Öppna filen i vscode

- **GIT**

  - git -v - kolla vilken version man har på GIT

  - git init - initialisera git på projeket

  - git clone länk - klona ett projekt som finns på t.ex github

  - git branch branchnamn - Skapa en ny branch

  - git switch branchnamn - byt branch

  - git merge branchnamn - merga branches, viktit att veta att man måste vara i den branchen man vill ha ändringarna till t.ex master innan man mergar in en annan branch

  - git branch -d branchnamn - ta bort branch när man mergat den

  - git status - se filer med ändringar i och om de e redo att comitta eller inte och även vilken branch man är på

  - git add filnamn - lägga till fil som man vill comitta till branchen

  - git commit -m"meddelande" - comitta filerna man lagt till som är redo att pushas med ett commit meddelande

  - git push - pusha det man har committat

  - git restor filnamn - ta bort alla nya ändringar i filen

  - git fetch - hämta ner nya ändringar som skett på repon (lokalt)

  - git pull - hämta ner alla nya ändringar som skett på repon

# Länkar

https://git-scm.com/docs/git

https://about.gitlab.com/images/press/git-cheat-sheet.pdf

https://www.markdownguide.org/basic-syntax/
