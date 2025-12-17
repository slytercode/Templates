# test-lavoro-collaborativo
## passaggi funzionanti per spostamento repo corretta:
1) creare cartella in locale per accogliere file
2) aprire cartella su folder vscode
3) copia il link alla repo originale
4) comando git clone + repo originale
5) comando cd per entrare nel file (qui ho individuato un errore, prima lavoravo sulla cartella originale, non switchavo nel suo file interno)
6) verifica stato con git status
7) verifica branch di partenza (dovrebbe essere la repo originale non tua del file)
8) crea nuova repo in remoto da github
9) assegna nuova repo con git remote set-url e url della repo appena creata su github 
