# Coffee - Divisione 1GC2506

Questo repository raccoglie iprogetti relativi allo spazio di lavoro Coffee-Div-1GC2506. Al momento questo spazio di lavoro è **temporaneo**, quindi non vanno salvati documenti o file che non siano stati salvati altrove, o file che non si vuole mantenere.

# Accesso ai repository tramite git client

* Creare un token di accesso personale seguendo la [seguente guida](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token).
  * Alla creazione del token verrà visualizzata la password del token, è l'unico momento in cui è possibile visualizzarla; se non la si riesce a recuperare o la si dimentica, andrà fatto un nuovo token.
* Dopo aver creato il token, autorizzarlo per accedere all'organizzazione IMA.
![image](https://user-images.githubusercontent.com/93708281/164390426-6f875561-07a2-4dd7-bdcc-4a287eb559f2.png)
* Usare nel client git le credenziali generate tramite token (l'username è quello dell'account github).
  * In alcuni casi i client richiedono la verifica del certificato ssl e questo può portare a un errore di connessione, in tal caso eseguire `git config http.sslVerify false`.


# Organizzazione dei progetti

Lo spazio dei progetti non è organizzato in cartelle, quindi si propone di mantenere organizzati i vari progetti utilizzando nomi con prefissi prestabiliti:

* hmi-
* plc-
* doc-
