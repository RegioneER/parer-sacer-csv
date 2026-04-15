 # CSV Sacer

 Progetto contenente i file csv per la gestione delle abilitazioni / permessi per applicazione web **sacer**. 

## CI/CD

Prevista una CI/CD al fine di gestire due aspetti: 
- l'ordinamento all'interno del singolo file csv 
- il mantenimento del branch **sviluppo**, che funge da contenitore di tutte le modifiche dei branch figli di master

**Nota**: il branch sviluppo è "modificabile" solo dagli utenti con profilo *mantainer* in quanto, è prevista una fase di merge delle modifiche effettuate nei branch figli di master sul branch sviluppo, di conseguenza solo il "super" utente può modificare tale branch

## Branch "sviluppo"

Si utilizzano i csv al suo interno da caricare con l'apposita funzione su interfaccia utente.
