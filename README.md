
# Progetto_GEP
Progetto GEP di Ghislanzoni Fabio 5IC

# PROBLEMA
Il problema che la web app mira a risolvere è l'organizzazione in modo compatto e semplice della propria routine di allenamento, avendo tutto in un unico ambiente

# TARGET 
Tutte le persone che praticano sport "inclusi" nell'applicazione

# SPECIFICA DEI REQUISITI

1. Autenticazione e registrazione di un utene (req. funz):
   - registrazione di un utente tramite e-mail e password
   - log-in nell'applicazione web e generazione della propria pagina personale
   - solo gli utenti registrati e autenticati potranno usufruire dell'applicazione
     
2. Creazione/inserimento della propria scheda/routine di allenamento (req. funz):
   - Assegnazione di un ID alla propria scheda/routine di allenamento
   - Possibilià di contrassegnare una scheda come "principale" o "attuale"
   - Inserimento di esercizi, tempi di recupero e carichi

3. Creazione/inserimento della propria scheda alimentare (req. funz):
   - Assegnazione di un ID alla propria scheda alimentare
   - Possibilità di contrassegnare una scheda come "principale" o "attuale"
   - Possibilità di associare una scheda alimentare ad una scheda/routin di allenamento
   - Inserimento di routine alimentare che potranno essere rinominate (es. colazione) e programmate (es. 7.00)

4. Invio di noifiche / Promemoria giornaliero per il proprio allenamento (req. funz):
   - possibilità di abilitare o disabilitare le notifiche di promemoria
  
5. Avvio dell'allenameno (req. funz):
   - Una volta iniziato l'allenamento, sarà possibile tenere traccia delle ripetizioni, dei carichi e dei recuperi
     - serie svolta: carichi, rep e recupero
     - serie non svolta: nessun dato

6. Possibilità di salvare/memorizzare un elenco di schede/alimentazioni (req. funz):
   - elenco di tutte le schede salvate dalla quale sarà possibile:
     - accedere e visualizzarne il contenuto
     - eliminarzione della scheda/alimentazione associata
     - "riutilizzo" della scheda/piano alimentare tramite l'opzione che permetterà di contrassegnarla come "attuale" o "corrente"

7. Resoconto generale del proprio percorso di allenamento basato sui dati forniti (req. funz):
 - Ogni volta che un allenamento verrà completato, sarà possibile visualizzare i propri progressi per ogni gruppo muscolare

8. Interfaccia utente user-friendly e facilmente comprensibile (req. non funz)

# SPECIFICA DEI CASI D'USO

1. Autenticazione e registrazione di un utene:
   > utente registrato, utente non registrato
   - In caso di utente non registrato:
     - registrazione andata a buon fine: l'utente, una volta registrato, potrà poi accedere all'applicazione tramite le credenziali
     - registrazione non andata a buon fine: l'utente potrà riprovare a registrarsi
   - In caso di utente già registrato:
     - Log-in andato a buon fine: l'utente accede all'applicazione e può utilizzarla a seconda delle necessità
     - Log-in non andato a buon fine: l'utente potrà riprovare a loggare, in caso di dimenticanze potrà richiedere la password per via e-        mail
2. Creazione/inserimento della propria scheda/routine di allenamento:
   > utente registrato, sistema
   - caso positivo: l'utente potrà creare una propria scheda di allenamento e inserirla nella sezione apposita
   - caso negativo: l'utente riceverà un messaggio di errore nel quale si specificherà cosa non è andato a buon fine

3. Creazione/inserimento della propria scheda alimentare
  > utente registrato, sistema
   - caso positivo: l'utente potrà creare una propria scheda di alimentazione e inserirla nella sezione apposita
   - caso negativo: l'utente riceverà un messaggio di errore nel quale si specificherà cosa non è andato a buon fine
  
4. Invio di noifiche / Promemoria giornaliero per il proprio allenamento
   > utente registrato, sistema
   - notifiche attive: l'utente riceverà le notifiche negli orari decisi e inseriti nel momento di creazione della scheda
   - notifiche non attive: l'utente non riceverà notifiche di promemoria

5. Avvio dell'allenameno:
   > utente registrato, sistema
   - caso positivo: l'utente potrà, di allenamento in allenamento, inserire il numero di ripetizioni e aggiungerlo a quelle precedenti
   - caso negativo: l'utente riceverà un messaggio di errore nel quale verrà specificato cosa non è andato a buon fine

6. Possibilità di salvare/memorizzare un elenco di schede/alimentazioni
    > utente registrato, sistema
   - caso positivo: la scheda di allenamento/alimentazione viene memorizzata correttamente in una sezione apposita
   - caso negativo: l'utente riceverà un messaggio di errore nel quale verrà specificato cosa non è andato a buon fine
  
7. Resoconto generale del proprio percorso di allenamento basato sui dati forniti:
    > utente registrato, sistema
   - caso positivo: l'utente potrà avere visione completa dei muscoli mirati durante l'allenamento accedendo a una sezione apposita
   - caso negativo: l'utente riceverà un messaggio di errore nel quale verrà specificato cosa non è andato a buon fine
  
# UML

![add236e6](https://github.com/FabioGhislanzoni/Progetto_GEP/assets/101174856/91b75527-97de-4e57-9ad0-1550e30c9730)

