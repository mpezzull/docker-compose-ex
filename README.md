# Esercizio

Modificare i file *docker-compose.yml, Dockerfile* ed *.env* per fare in modo che il progetto possa essere lanciato con il comando:

`docker compose up`

Una volta avviato il progetto, entrare nel container relativo al db (mysql) ed inserire una riga nella tabella "Tutorials" del database "db".

Al link ` localhost:<port>/api/tutorials` potrete vedere la lista di tutti gli oggetti Tutorials inseriti.

Fermate il progetto con il comando:

 *docker compose down*

e rilanciatelo con il comando up, i dati che avete inserito devono essere ancora presenti.
