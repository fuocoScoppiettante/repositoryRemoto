# Git - Working with Remotes
* I reposity remoti sono versioni del tuo progetto che sono ospitate su Internet
* La collaborazione con altri programmatori implica la gestione di questi reposity e il push e il pull di dati

Fondamentalmente è saper **sincronizzare il nostro lavoro locale con un reposity remoto.**

comandi principali:

`git remote -v` --> visualizza i server remoti collegati al nostro reposity

### Aggiungere o rimuovere un reposity remoto

`git remote add <nome> <url>` 

### Caricare il lavoro sul reposity remoto

`git push <remote> <ramo-locale>`

### Aggiornare la copia locale del reposity, allineando con la versione remota

`git pull <remote> <ramo-locale>`
