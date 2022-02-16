<img src="https://github.com/dadoPuccio/Prenota-Biblio-Unifi/blob/main/images/logo.svg" alt="Logo" loading="lazy" style="width:200px;">

# Prenota-Biblio Unifi
Progetto per **automatizzare la prenotazioni** delle **Biblioteche** ed **Aule Studio** dell'ateneo fiorentino.       
Parte dell'esame di Human Computer Interaction A.A. 2021-2022.

Studente: Davide Pucci    
Modalità esame: 9 cfu

## Abstract
A seguito dell'introduzione di **Kairos**, il sistema informativo che consente la prenotazione dei servizi bibliotecari dell'ateneo di Firenze, ogni studente che voglia accedere a una Biblioteca o ad un'Aula Studio è costretto a prenotarsi online appena il periodo di prenotazioni si apre (spesso durante la notte) per evitare il rischio di trovare tutti i posti già occupati. Sviluppiamo qui l'idea di un'applicazione che consenta la **prenotazione automatica al servizio**, così da svincolare gli studenti da questi orari e assicurargli i posti negli spazi studio.

## Risultati Attesi
Ci aspettiamo di:
- Attraverso una procedura di Need-Finding, di aver identificato le personas, gli scenari e i requisiti propri dell'applicazione in questione.
- Offrire un prototipo funzionante dell'applicazione di prenotazione automatica, che risponda alle necessità delineate durante il Need-Finding.
- Aver effettuato un'analisi del prodotto finito, attraverso un Usability Testing.

## Implementazione e Funzionalità
L'applicazione è stata implementata usando [Flutter](https://flutter.dev/): un framework open-source che consente di creare applicazioni multi-platform da un unico sorgente. Prenota-Biblio Unifi è dunque pensata per funzionare sia su **Android** che su **iOS**.

Di seguito sono riportati alcune delle schermate della app:

_Schermata di login_  
<img src="https://github.com/dadoPuccio/Prenota-Biblio-Unifi/blob/main/images/login.png" alt="Logo" loading="lazy" style="width:250px;">

_Home Page_  
<img src="https://github.com/dadoPuccio/Prenota-Biblio-Unifi/blob/main/images/home.png" alt="Home Page" loading="lazy" style="width:250px;">

_QR di accesso_  
<img src="https://github.com/dadoPuccio/Prenota-Biblio-Unifi/blob/main/images/qr.png" alt="QR Access" loading="lazy" style="width:250px;">

_Calendario per visualizzare e gestire le prenotazioni_  
<img src="https://github.com/dadoPuccio/Prenota-Biblio-Unifi/blob/main/images/calendario.png" alt="Calendar" loading="lazy" style="width:250px;">


L’applicazione inoltre è abilitata all’uso delle _notifiche_. Tramite queste offre all’utente dei **reminder** per ricordare le prenotazioni per il giorno successivo, cosı̀ che sia ancora possibile effettuare delle eliminazioni:   

_Reminder di Prenotazione_   
<img src="https://github.com/dadoPuccio/Prenota-Biblio-Unifi/blob/main/images/remider.gif" alt="Reminder" loading="lazy" style="width:250px;">

Sempre tramite le notifiche viene chiamato il bot di prenotazione notturno: tutte le volte che è possibile **effettuare una prenotazione durante la notte**, a mezzanotte si ha una **notifica** di tipologia **full-screen** che permette di portare a termine le prenotazioni.

_Bot di Prenotazione Notturno_  
<img src="https://github.com/dadoPuccio/Prenota-Biblio-Unifi/blob/main/images/bot.gif" alt="Reminder" loading="lazy" style="width:250px;">


Maggiori dettagli sono disponibili sul [report](https://github.com/dadoPuccio/Prenota-Biblio-Unifi/blob/main/report_PrenotaBiblioUnifi.pdf).


## Note
- Il codice dell'applicazione non viene rilasciato pubblicamente per scelta dell'autore.
- Il logo è stato fatto componendo due immagini svg trovate su [pixabay](https://pixabay.com/), unendo un calendario e un giglio. Come colori dell'interfaccia sono stati impiegati gli stessi di [unifi.it](https://www.unifi.it/).
