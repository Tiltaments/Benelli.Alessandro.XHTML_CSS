PROGETTO: Sito Web "Palestra 648"
CORSO: Sviluppo Web - Homework 1 (XHTML/CSS)

AUTORI DEL GRUPPO:

- Alessandro Benelli

REPOSITORY GITHUB:

- URL del repository di Nome Cognome 1: https://github.com/...

DESCRIZIONE E TECNICHE UTILIZZATE:
Il sito web presenta una palestra fittizia. È composto da diverse pagine statiche scritte in XHTML 1.0 Strict per garantire la validazione e la corretta struttura semantica.
Il layout è gestito interamente tramite un file CSS esterno.
È stato implementato un layout con menu laterale fisso (fixed positioning) per facilitare la navigazione e un footer fisso per i contatti rapidi. Non sono state utilizzate tabelle per il layout, ma solo elementi <div> posizionati tramite CSS.

================================ SCHERMO DEL BROWSER ================================

+--------------------+--------------------------------------------------------------+
|                    |                                                              |
|   #sidebar         |   #content                                                   |
|                    |                                                              |
| (Largo 200px,      | (Spostato a destra con margin-left: 200px per non finire     |
|  fisso a sinistra, |  sotto il menu laterale)                                     |
|  alto 100%)        |                                                              |
|                    |       +----------------------------------------------+       |
|  [ La Mia Palestra]|       |                                              |       |
|                    |       |  .main-image                                 |       |
|  - HOME            |       |  (L'immagine non supera i confini grazie a   |       |
|  - PACCHETTI       |       |   max-width: 100% e max-height: 300px)       |       |
|  - SERVIZI         |       |                                              |       |
|  - TRAINER         |       +----------------------------------------------+       |
|  - CONTATTI        |                                                              |
|                    |       <h1>Titolo della Pagina (es. I Nostri Servizi)</h1>    |
|                    |                                                              |
|                    |       <p>Testo descrittivo del contenuto centrale...</p>     |
|                    |                                                              |
|                    |       <ul>                                                   |
|                    |          <li>Elemento lista 1</li>                           |
|                    |          <li>Elemento lista 2</li>                           |
|                    |       </ul>                                                  |
|                    |                                                              |
|                    |                                                              |
|                    |                                                              |
+--------------------+--------------------------------------------------------------+
|   (Spazio vuoto    |   #footer                                                    |
|    invisibile del  |                                                              |
|    footer, bloccato| (Fisso in basso con bottom: 0, ma inizia a 200px da sinistra |
|    sotto il menu)  |  con left: 200px per occupare solo l'area sotto al #content) |
+--------------------+--------------------------------------------------------------+
