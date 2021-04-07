| *Progetto:* GPOI_papini_cherubini     | Codice progetto: 00JF |
| ------------------------------------- | --------------------- |
| ***Data:*** 06/04/2021                | ***Revisione:*** 0    |
| ***Cliente:*** Assessorato al Turismo | ***Sponsor:*** null   |

---

1.**OBIETTIVI:**

Realizzare un'infrastruttura tecnologica che offra ai visitatori un servizio per la fruizione di contenuti multimediali che descrivono i "*punti di interesse*" (*POI --> Point of Interest*) di tipo monumentale (*es. chiese, luoghi storici, ecc...*) e artistico (*es. musei, mostre, ecc...*) distribuiti nel centro storico della città.

---

2.**PRINCIPALI DELIVERABLE:**

***Project Management:*** Pianificazione del progetto.

***Project Management:*** Analisi e specifiche del progetto.

***Progettazione (P0):*** Acquisire immagini dei POI.

***Progettazione:*** Progettare i contenuti multimediali sotto forma di pagine web (HTML e PHP).

***Progettazione (P1):*** Progettare la pagina multimediale di base (PMB).

    ***Progettazione:*** Creazione video presentazione per PMB.

    ***Progettazione:*** Caricare immagini dei POI, aggiungere didascalia in IT e EN.

***Progettazione (P2):*** Progettare la pagina multimediale avanzata (PMA).

    ***Progettazione:*** Creazione video presentazione per PMA.

    ***Progettazione:*** Caricare immagine dei POI, aggiungere didascalia (*media 500 caratteri*) in IT e una lingua tra le 7 possibili.

***Progettazione (P3):*** Progettare un sistema che gestisca le 3 tariffe disponibili (*tariffa base, tariffa intermedia, tariffa piena*).

***Progettazione (P3):*** Progettare sistema di login ai contenuti tramite password.

---

3.**MILESTONE:**

**P0:** Noleggiare una fotocamera e un drone per fotografare ogni POI del centro storico della città per ottenere le immagini da caricare nelle pagine multimediali. Eventuali fotografie verranno poi ritoccate con Photoshop.

**P1:** Progettare in HTML e PHP la PMB, con al suo interno un breve video del POI (*1 minuto circa*) in italiano con sottotitoli in inglese, il video sarà progettato e creato dal montatore video, mentre i sottotitoli in lingua inglese verranno affidati ad un traduttore specializzato. Successivamente aggiungere un massimo di 3 immagini relative al POI (*di quelle scattate nel P0*) con relativa didascalia in italiano ed inglese affidata al traduttore. Verranno utilizzati VisualStudioCode per la progettazione e DaVinciResolve per la creazione dei video. I contenuti saranno salvati e contenuti in un server.

**P2:** Progettare in HTML e PHP la PMA, con al suo interno un video di presentazione approfondito del POI (*5 minuti circa*) in una fra 7 lingue possibili compreso l'italiano, il video sarà progettato e creato dal montatore video, mentre la traduzione in lingua inglese verranno affidati ad un traduttore specializzato. Successivamente aggiungere una galleria di una ventina di immagini relative al POI (*di quelle scattate nel P0*) con relativa descrizione (*500 caratteri circa*) in una fra 7 possibili lingue compreso l'italiano, le traduzione saranno affidate al traduttore. I contenuti saranno salvati e contenuti in un server. Per gestire il server verrà utilizzato Xampp.

**P3:** La gestione delle 3 tariffe verrà gestita dall'InfoPoint, il quale in base al prezzo pagato dal cliente (*Ipotesi: tariffa base 5€, tariffa intermedia 10€, tariffa piena 15€*) fornirà una password associata al tipo di tariffa. Le password saranno memorizzate all'interno di un DataBase all'interno del server. Successivamente è opportuno progettare un sistema di login in PHP mediante l'utilizzo delle password salvate nel DataBase. Per gestire il DataBase verrà utilizzato PostgreeSQL.

---

4.**VINCOLI E DIPENDENZE:**

Il cliente richiede che siano soddisfatti i seguenti vincoli:

- La consultazione delle pagine multimediali  sia abilitata **esclusivamente** ai dispositivi (*minitablet*) forniti all'atto dell'acquisto del biglietto, previa consegna di un documento di identità o di un numero di carta di credito valida.

- Memorizzazione dei contenuti esistenti su **sistemi server** e **non su dispositivi utilizzati**, per favorire l'aggiornamento dei contenuti esistenti o l'aggiunta di nuovi contenuti.

- L'accesso alle pagine multimediali sia effettuabile **esclusiamente** dopo l'inserimento della password presente nel bliglietto.

- L'accesso alle pagine multimediali relative ad un POI debba avvenire **solo** in prossimità o all'interno del POI stesso.

- La restituzione dei dispositivi (*minitablet*) possa avvenire presso l'InfoPoint che ha in custodia il documento di identità oppure presso un qualsiasi InfoPoint se il visitatore ha optato per lasciare il numero di carta di credito valida.

---

5.**TEMPISTICA PRELIMINARE:**

**Pianificazione, analisi e specifiche del progetto:** dal 19 aprile 2021 al 30 aprile 2021.

**P0:** dal 3 maggio 2021 al 16 maggio 2021

**P1 & P2:** dal 19 maggio 2021 al 18 giugno 2021

**P3:** dal 21 giugno 2021 al 2 luglio 2021

**Test e risoluzione eventuali errori:** dal 10 luglio 2021 al 23 luglio 2021

**Consegna progetto:** dal 26 luglio 2021 al 30 luglio 2021

[Diagramma di Gantt](https://github.com/giorgimuratore/POI-WiFi/blob/main/Diagramma%20di%20Gantt%20GPOI/Diagramma%20di%20Gantt.html)

---

6.**PRINCIPALI RISORSE E LIMITI DI COSTO:**

Il progetto avrà un costo di 20.000€ circa.

Il noleggio di una fotocamera professionale avrà un costo di 35€ al giorno (x 14 giorni), quindi un totale di 490€.

Il noleggio di un drone per le riprese e le fotografie avrà un costo di 350€.

La licenza del software Photoshop avrà un costo di 20€ al mese.

Il server che verrà utilizzato avrà un costo di 3.000€ circa.

I software non citati sono gratuiti.

Il traduttore specializzato in 7 lingue avrà un costo medio di 15€/h.

Il montatore video avrà un costo medio di 20€/h.

I tecnici impiegati nella progettazione sono interni all'azienda, i cui costi sono ben definiti dai 20 ai 40€/h.

Da considerare i costi della rete internet, i costi dell'elettricità, i rimborsi spese per il montatore video (*il traduttore lavorerà a distanza*).

Il materiale non citato (*es computer, postazioni, ecc...*) sono gia posseduti dall'azienda.

---

7.**DOCUMENTI DI RIFERIMENTO E ALLEGATI:**

- [Documento PDF con richieste del cliente](https://www.istruzione.it/esame_di_stato/201819/Istituti%20tecnici/Ordinaria/AB51_ORD19.pdf)

---
