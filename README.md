# MYG-PPW
Cartella contenente il progetto realizzato per il corso di Progettazione per il Web (a.a. 2018/2019) del CdL in Informatica e Comunicazione Digitale sede di Taranto.

<b>Istallazione rapida in Windows </b>

Scaricare il webserver UwAmp dal seguente link, contenente la versione del progetto.
Scompattare l'archivio in una cartella del PC, es. C:

Entrare nella sotto cartella e avviare UwAmp.exe come amministratore. 
Utilizzando l'ultima versione di Google Chrome aprire il seguente link: http://localhost/ProgettoFinale/Progetto/MYG/public


<b>Installazione manuale in Windows</b>
<ul>
  <li>Scaricare il composer dal seguente link https://getcomposer.org/ </li>
  <li>Portarsi tramite il prompt dei comandi nella cartella C:\xampp\htdocs</li>
  <li>digitare il comando <i>git clone https://github.com/AttilioIurlaro/Iurlaro-PPW.git Progetto</i> per clonare il progetto nella cartella progetto</li>
  <li>digitare <i>cd progetto</i></li>
  <li>digitare <i>cd MYG</i></li>
  <li>digitare <i>composer install</i></li>
  <li>digitare <i>composer update</i></li>
  <li>creare il database da phpmyadmin di nome <i>myg</i></li>
  <li>Se si ha bisogno di settare le impostazioni globali, andare nel file <i>.env</i>: </li>
  <ul>
    <li>impostare la DB_CONNECTION con il tipo di connessione al db (mysql)</li>
    <li>impostare il DB_DATABASE con il nome del database da utilizzare (myg) precedentemente creato e privo di tabelle e dati</li>
    <li>impostare la DB_USERNAME con un eventuale nome utente per il db (root è impostata di default)</li>
    <li>mpostare la DB_PASSWORD con una eventuale password per l'utente del db</li>
  </ul>
  <li>Digitare <i>php artisan migrate:fresh</i></li>
  <li>Digitare <i>php artisan db:seed</i></li>
  <li>Digitare <i>php artisan serve</i></li>
  <li>Avviare il sito dal seguente link http://localhost/ProgettoFinale/Progetto/MYG/public</li>
</ul>

<b>La connessione ad internet è richiesta</b>


Realizzato da:
<ul>
  <li>Andrea Carbone</li>
  <li>Roberta Della Ricca</li>
  <li>Andrea Iacobino</li>
  <li>Attilio Iurlaro</li>
  <li>Germana Spinelli</li>
  <li>Francesco Sternativo</li>
</ul>
