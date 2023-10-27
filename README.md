# homeassistant-docker-compose

In questo repository trovi il file `docker-compose.yml` utile per creare una installazione di test di Home Assistant sul tuo computer.

Per lanciare il programma:
- Assicurati di avere Docker installato sul tuo computer (https://docs.docker.com/get-docker/)
- Scarica il file `docker-compose.yml` sul tuo computer e mettilo in una cartella di tua scelta
- Posizionati con il terminale/Powershell nella cartella contenente il file appena scaricato
- Esegui il comando `docker compose up`

Attendi che Docker scarichi l'immagine di Home Assistant e lo metta in esecuzione, dopo di che apri nel browser la pagina:

<code>http://localhost:8123</code>

Da qui in avanti, puoi fare riferimento alla documentazione ufficiale per orientarti sulla tua prima installazione di Home Assistant: https://www.home-assistant.io/docs/configuration/
