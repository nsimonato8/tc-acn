# README

## Descrizione

Questa repository è un'implementazione della “Tassonomia Cyber dell’Agenzia per la Cybersicurezza Nazionale” (TC-ACN), ossia il linguaggio comune per lo scambio delle informazioni relative a
eventi e minacce di cybersicurezza, così come definita nella [pubblicazione](https://csirt.gov.it/contenuti/la-tassonomia-cyber-dellacn) del 31/07/2024. 

Questa implementazione consente di utilizzare i tag definiti in TC-ACN nella piattaforma per la Cyber Threat Intelligence [MISP](https://www.misp-project.org/).

## Aggiungere TC-ACN alla propria istanza MISP

Per aggiungere questa tassonomia alla propria istanza MISP è sufficiente seguire le informazioni riportate qui di seguito:

 * Creare una cartella con il nome della tassonomia (es. TC-ACN) all'interno del percorso `/var/www/MISP/app/files/taxonomies/` (nei sistemi Linux)
 * Aggiungere il file `machinetag.json`
 * Dall'interfaccia grafica del MISP: "**List Taxonomies $\rightarrow$ Update Taxonomies**"
 * Abilitare la tassonomia e i singoli tag.

