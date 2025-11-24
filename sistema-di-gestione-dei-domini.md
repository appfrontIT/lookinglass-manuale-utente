# Sistema di Gestione dei Domini

### Sistema di Gestione dei Domini&#x20;

Il **Sistema di Gestione dei Domini** consente a **Lookinglass** di gestire l’accesso e la visibilità tra diversi ambienti aziendali.\
Ogni compagnia o intermediario (ad esempio **WAKAM**, **DALLBOGG** o **DAS**) opera sotto il proprio dominio, garantendo che gli utenti possano accedere solo ai dati appartenenti alla propria organizzazione.

***

#### Scopo

Il sistema dei domini è stato introdotto per separare utenti, aziende e dati tra le diverse entità che operano all’interno dello stesso ambiente di **Lookinglass**.\
Ogni dominio rappresenta l’ambiente unico di una compagnia o di un intermediario (ad esempio `dalbog.ipagency.it`).\
In questo modo, gli utenti registrati sotto una compagnia non possono accedere ai domini o ai dati di un’altra.\
Il controllo degli accessi è automatico ed effettuato al momento del login.

***

#### Funzionamento

**Definizione del Dominio**

* Ogni dominio corrisponde a un indirizzo web (ad esempio `lookinglass.ipagency.it` o `wakam.ipagency.it`).
* Solo i **Super Admin** di IPA possono creare, modificare o eliminare domini.
* Ogni dominio è collegato a una o più compagnie.

**Associazione delle Aziende**

* Una compagnia può avere **più domini**.
* Un dominio può essere condiviso da **più compagnie** (ad esempio intermediari appartenenti allo stesso gruppo principale).
* Durante la creazione o modifica di una compagnia, gli utenti autorizzati possono aggiungere o rimuovere i domini associati.

**Controllo degli Accessi**

* Quando un utente effettua il login, il sistema verifica se la compagnia a cui appartiene è collegata al dominio a cui sta accedendo.
* Se il dominio **non è autorizzato** per la sua compagnia, l’accesso viene negato con un messaggio chiaro.
* Questo meccanismo impedisce l’accesso incrociato tra intermediari diversi.

***

#### Dominio Predefinito

* Il primo dominio predefinito è **lookinglass.ipagency.it**.
* Quando vengono create nuove compagnie, queste vengono automaticamente assegnate allo **stesso dominio della compagnia madre**.
* Se la compagnia non ha una compagnia madre (livello principale), solo un **Super Admin** può scegliere il dominio.

***

#### Permessi

* **Super Admin**: accesso completo per creare, modificare e rimuovere domini.
* **Admin**: possono visualizzare e assegnare i domini esistenti alle proprie compagnie (se autorizzati).
* **Utenti Standard**: non possono visualizzare né modificare i domini.

***

#### Esempio Pratico

* **WAKAM** opera sotto il dominio `wakam.ipagency.it` e ha il codice intermediario **935**.
* Diverse sotto-compagnie (intermediari) lavorano sotto il dominio di WAKAM.
* Un utente creato sotto **DALLBOGG** (`dallbogg.ipagency.it`) **non può accedere** tramite il dominio di **WAKAM**.
* Questo garantisce una separazione rigorosa tra gli ambienti e impedisce accessi non autorizzati tra compagnie diverse.

Il **Sistema di Gestione dei Domini** consente a **Lookinglass** di gestire l’accesso e la visibilità tra diversi ambienti aziendali.\
Ogni compagnia o intermediario (ad esempio WAKAM, DALLBOGG o DAS) opera sotto il proprio dominio, garantendo che gli utenti possano accedere solo ai propri dati.

***

#### Scopo

Il sistema dei domini è stato introdotto per separare utenti, aziende e dati tra le diverse entità che operano all’interno dello stesso ambiente di **Lookinglass**.\
Ogni dominio rappresenta l’ambiente unico di una compagnia o di un intermediario (ad esempio `dalbog.ipagency.it`).\
In questo modo, gli utenti registrati sotto una compagnia non possono accedere ai domini o ai dati di un’altra.\
Il controllo degli accessi è automatico ed effettuato al momento del login.

***

#### Funzionamento

**Definizione del Dominio**

* Ogni dominio corrisponde a un indirizzo web (ad esempio `lookinglass.ipagency.it` o `wakam.ipagency.it`).
* Solo i **Super Admin** di IPA possono creare, modificare o eliminare domini.
* Ogni dominio è collegato a una o più compagnie.

**Associazione delle Aziende**

* Una compagnia può avere **più domini**.
* Un dominio può essere condiviso da **più compagnie** (ad esempio intermediari appartenenti allo stesso gruppo principale).
* Durante la creazione o modifica di una compagnia, gli utenti autorizzati possono aggiungere o rimuovere i domini associati.

**Controllo degli Accessi**

* Quando un utente effettua il login, il sistema verifica se la compagnia a cui appartiene è collegata al dominio a cui sta accedendo.
* Se il dominio **non è autorizzato** per la sua compagnia, l’accesso viene negato con un messaggio chiaro.
* Questo meccanismo impedisce l’accesso incrociato tra intermediari diversi.

***

#### Dominio Predefinito

* Il primo dominio predefinito è **lookinglass.ipagency.it**.
* Quando vengono create nuove compagnie, queste vengono automaticamente assegnate allo **stesso dominio della compagnia madre**.
* Se la compagnia non ha una compagnia madre (livello principale), solo un **Super Admin** può scegliere il dominio.

***

#### Permessi

* **Super Admin**: accesso completo per creare, modificare e rimuovere domini.
* **Admin**: possono visualizzare e assegnare i domini esistenti alle proprie compagnie (se autorizzati).
* **Utenti Standard**: non possono visualizzare né modificare i domini.

***

#### Esempio Pratico

* **WAKAM** opera sotto il dominio `wakam.ipagency.it` e ha il codice intermediario **955**.
* Diverse sotto-compagnie (intermediarie) lavorano sotto il dominio di WAKAM.
* Un utente creato sotto **DALLBOGG** (`dallbogg.ipagency.it`) **non può accedere** tramite il dominio di **WAKAM**.
* Questo garantisce una separazione rigorosa tra gli ambienti e impedisce accessi non autorizzati tra compagnie diverse.
