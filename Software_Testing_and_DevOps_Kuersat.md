# DevOps & Testing

## Review

Ticket [#104](https://github.com/SEPMFWS422A/time2meet/issues/104)

**Ziel:** <br/> 
- Es sollten nach Fehlern / Unnötigen Code geschaut werden die dann als Review festgehalten werden sollte


**Commits**
[ba6101b](https://github.com/SEPMFWS422A/time2meet/commit/ba6101bd0c5dd77201bd689bde14fdacaec5d924#r153420085): <br/>
  - Im Code als Kommentar verfasst was entfernt werden soll


## Selbstbearbeitete Tickets

Ticket [#59](https://github.com/SEPMFWS422A/time2meet/issues/59)
**Ziel:** 
- Es sollte für die Komponente Profilsetting eine Umfassende End To End Test mit Cypress geschrieben werden
- Alle Commits in der Tabelle bilden das Ziel ab  

**Commits**

[f78b35c](https://github.com/SEPMFWS422A/time2meet/commit/f78b35cbd4e527750d3a329100bd37bee18444ef): <br/>
  - Initiale Erstellung der End to End Test für Profilsettings

[c6dd20d](https://github.com/SEPMFWS422A/time2meet/commit/c6dd20dd4e21f70da0ac2ed14796e91a08322a95): <br/>
  - Anpassung und Erweiterung der End to End Test für Profilsettings
  
[cd19dd1](https://github.com/SEPMFWS422A/time2meet/commit/cd19dd1343b5706c708274803a74c2e33a2a4783): <br/>
  - Anpassung des End to End Test für Profilsettings (Login wurde hinzugefügt)

Ticket [#139](https://github.com/SEPMFWS422A/time2meet/issues/139)
**Ziel:** 
- Es sollte für die Komponente Friendlist eine Umfassende End To End Test mit Cypress geschrieben werden
- Alle Commits in der Tabelle bilden das Ziel ab  

**Commits**

[88c39c6](https://github.com/SEPMFWS422A/time2meet/commit/88c39c601ee27ffd2dd5338af5fec1f140054afb): <br/>
  - End To End Test Friendlist hinzugefügt (Mit beachtung des modals für Freundessuche)
  - Friendlist Komponente Erweitert, um die IDs (suche für E2E vereinfacht)
  - Performenz Placeholder entfernt

Ticket [#140](https://github.com/SEPMFWS422A/time2meet/issues/140)
**Ziel:** 
- Es sollte für die gesamtes Freundes API eine Umfassende Unit mit Jest geschrieben werden
- Alle Commits in der Tabelle bilden das Ziel ab  

**Commits**

[c9ea128](https://github.com/SEPMFWS422A/time2meet/commit/c9ea128c0a69b5530e5b1922c7ce56dd82a6f86c): <br/>
  - Unit Test für Freunde Hinzufügen API erstellt
  - Unit Test für Freunde Entfernen API erstellt
  - Unit Test für Freundessuche API erstellt
  - Unit Test für die Freundesanzeige erstellt

Ticket [#141](https://github.com/SEPMFWS422A/time2meet/issues/141)
**Ziel:** 
- Es sollte für die gesamtes User API eine Umfassende Unit mit Jest geschrieben werden
- Alle Commits in der Tabelle bilden das Ziel ab  

**Commits**

[3a09aa6](https://github.com/SEPMFWS422A/time2meet/commit/3a09aa6ad5c1ba8a8c5f825e5031f69b5e9d8bdb): <br/>
  - Kompletter Unit Test für die komplette User API

[1995e98](https://github.com/SEPMFWS422A/time2meet/commit/1995e98d52437bc48d4e261abdab6f91762eb392): <br/>
  - Anpassung des Unit Test (Lesbarkeit angepasst)

[2fc9083](https://github.com/SEPMFWS422A/time2meet/commit/2fc90838160db69ffbb0a7f3e334672b9e022b6f): <br/>
  - Anpassung des Unit Test (Struktur angepasst von it auf test (wurde wieder entfernt in Commit 684ab9c, daher nicht beachten))

[046033a](https://github.com/SEPMFWS422A/time2meet/commit/046033a457d0b8cec840ad82d68c8c1d3a3e44b5): <br/>
  - Anpassung des Unit Test ( Status anpassung nach Feedback)

[684ab9c](https://github.com/SEPMFWS422A/time2meet/commit/684ab9cdd81f61b051fbdf32762029e44da1fd24): <br/>
  - Struktur  des Unit Test angepasst(von test auf it )

Ticket [#142](https://github.com/SEPMFWS422A/time2meet/issues/142)
**Ziel:** 
- Hier sollte nur die Get Anfrage der Umfrageliste geprüft werden mit jest
- Alle Commits in der Tabelle bilden das Ziel ab  

**Commits**

[684ab9c](https://github.com/SEPMFWS422A/time2meet/commit/684ab9cdd81f61b051fbdf32762029e44da1fd24): <br/>
  - Unit Test für "Participatinglist" hinzugefügt


Ticket [#176](https://github.com/SEPMFWS422A/time2meet/issues/176)
**Ziel:** 
-  Hier sollte die Integrationstest für Freundliste erstellt werden
- Alle Commits in der Tabelle bilden das Ziel ab

**Commits**

[7eaa54a](https://github.com/SEPMFWS422A/time2meet/commit/7eaa54a733bff7a612501b6dc025e2616284c39b): <br/>
  - Integration Test mit jest für Friendlist erstellt

Ticket [#177](https://github.com/SEPMFWS422A/time2meet/issues/177)
**Ziel:** 
-  Hier sollte die Integrationstest für Profilsettings erstellt werden
- Alle Commits in der Tabelle bilden das Ziel ab 

**Commits**

[782167f](https://github.com/SEPMFWS422A/time2meet/commit/782167f14668012d57403058a55379f891b945b4): <br/>
  - Integration Test mit jest für Profilsettings erstellt

## **Kollaborative Tickets**

Ticket [#13](https://github.com/SEPMFWS422A/time2meet/issues/13)
**Ziel:**
- Es sollte für die Generierung des .ics Dateis die Integrations Test erstellt werden.
- Zum damaligen Zeitpunkt wurde der Test mit Cypress geschrieben
- Alle Commits in der Tabelle bilden das Ziel ab und ist als ganzes Ticket zu bewerten mit dem Anteil 50/50 Kürsat Darcan / Timo Neuhaus

**Commits**

[1e5371b](https://github.com/SEPMFWS422A/time2meet/commit/1e5371b5d3552a5f3181461e407d2b6f0993f998): <br/>
  - Integration Test mit Cypress für das generierte ICS Datei erstellt in dem geprüft wird ob der Inhalt mit dem Kalendar Inhalt übereinstimmt

[9b844c4](https://github.com/SEPMFWS422A/time2meet/commit/9b844c4bee6cf7061eaa74266988727df781e3ed): <br/>
  - Anpassung vorgenommen, das die werte nicht Statisch sondern Dynamisch getestet werden, wenn mehr Events hinzugefügt wird

Ticket [#106](https://github.com/SEPMFWS422A/time2meet/issues/106)
**Ziel:** 
- Ziel war es das Framework Jest ins Anwendung aufzunehmen.
- Per Pair Programming wurde das auf einem Rechner gemacht und hinzugefügt
- Alle Commits in der Tabelle bilden das Ziel ab und ist als ganzes Ticket zu bewerten mit dem Anteil 33.3% Kürsat Darcan / Timo Neuhaus / Mohamed El Marraki

**Commits**

[a3d0a54](https://github.com/SEPMFWS422A/time2meet/commit/a3d0a54aa151978879f054d8a7e30f59ab3d61ea): <br/>
  - Integration Konfiguration von Jest
