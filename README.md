# Ontologie e Vocabolari Controllati

**TRANNE DOVE DIVERSAMENTE SPECIFICATO, LE ONTOLOGIE SI INTENDONO ANCORA INSTABILI. NEL CORSO DELLE PRIME SETTIMANE DI MARZO 2018 SE NE STABILIZZERANNO ALCUNE DI SEGUITO ELENCATE.**


Questo è il repository delle ontologie e dei vocabolari controllati sviluppati nell'ambito delle azioni previste dal piano triennale e a supporto del lavoro da svolgere per l'[elenco delle basi di dati chiave](http://elenco-basi-di-dati-chiave.readthedocs.io/it/latest/).
Le ontologie create sono tra loro collegate creando una vera e propria network chiamata **OntoPiA** - a OntoNet system. Le ontologie saranno inserite nel catalogo delle ontologie e vocabolari controllati (si veda la parte [daf-semantics](https://github.com/italia/daf-semantics) e [ontonethub](https://github.com/teamdigitale/ontonethub) per il software relativo al catalogo).


![OntoPiA](OntoPiA.png)

Il repository è suddiviso in due directory:

  + **Ontologie (Ontologies)**: contiene le ontologie OWL, serializzate in RDF/Turtle RDF/XML e JSON-LD. I diagrammi UML delle ontologie sono attualmente in fase di definizione e revisione a seguito dei collegamenti abilitati tra tutte le ontologie. Le ontologie hanno label e commenti sia in inglese (EN), sia in italiano (IT).
  + **Vocabolari controllati (Controlled Vocabularies)**: contiene un elenco dei vocabolari controllati sviluppati anche a supporto delle ontologie.

Il contenuto della directory **Ontologie** è attualmente il seguente:

  + **IoT (IoT Events - Eventi IoT - IoT-AP_IT) [DOC](https://w3id.org/italia/onto/IoT)**: Ontologia del profilo applicativo italiano degli eventi IoT (IoT-AP_IT - IoT Italian Application Profile). **Questa ontologia può ritenersi stabile**
  + **CPV (People - Persone - CPV-AP_IT) [DOC](https://w3id.org/italia/onto/CPV)**: Ontologia del profilo applicativo italiano sulle persone (CPV-AP_IT - Core Person Vocabulary-Italian Application Profile). La versione 0.4 (e da lì tutte le seguenti) è stata definita insieme all'ISTAT nell'ambito dei lavori di ISTAT relativi ai propri registri interni. Nella directory relativa all'ultima versione attuale dell'ontologia vi è anche il file con i relativi allineamenti a ontologie esterne del Web (e.g., FOAF). Per convenzione i file di allineamento sono chiamati "acronimoOntologia-aligns-AP_IT" (in questo caso CPV-aligns-AP_IT). **Questa ontologia è da ritenersi stabile**
  + **COV (Organizzazioni - Organizations - COV-AP_IT) [DOC](https://w3id.org/italia/onto/COV)**: Ontologia del profilo applicativo italiano sulle organizzazioni (pubbliche e private) (COV-AP_IT - Core Organization Vocabulary - Italian Application Profile). E' presente il file di allineamneti a ontologie esterne del Web quali Org, RegOrg, Core Public Organization Vocabulary, ecc.; **Questa ontologia è in fase di revisione. E' quindi da considerarsi instabile**
  + **CLV (Indirizzi/luoghi - Addresses/Locations - CLV-AP_IT) [DOC](https://w3id.org/italia/onto/CLV)**: Ontologia del profilo applicativo italiano sugli indirizzi e luoghi (CLV-AP_IT - Core Location Vocabulary - Italian Application Profile). E' presente il file con gli allineamenti a ontologie esterne del Web (e.g., Core Location Vocabulary, AD conforme a INSPIRE, GeoSparql, Geonames, ecc.). **Disponibile la versione stabile 1.0 dell'ontologia corredata degli elementi dell'ontologia disponibili come struttura tabellare e di un esempio pratico in RDF**;
  + **SM (Internet e Social Media- SM-AP_IT) [DOC](https://w3id.org/italia/onto/SM)**: Ontologia di supporto. Essa è il profilo applicativo italiano per la modellazione dei social media (account dei social network) e delle informazioni di contatto digitali (quali sito web istituzionale, indirizzo email, loghi), utilizzate in altre ontologie di OntoPiA. **Questa ontologia è da ritenersi stabile**
  + **TI (Tempo - Time - TI-AP_IT)  [DOC](https://w3id.org/italia/onto/TI)**: Ontologia di supporto del tempo utilizzata in molte ontologie di OntoPiA per cogliere la dimensione temporale dei principali concetti. **Questa ontologia è da ritenersi stabile**
  + **POI (Punti di interesse - Points of Interest - POI-AP_IT)  [DOC](https://w3id.org/italia/onto/POI)**: Ontologia del profilo applicativo italiano sui punti di interesse. E' un'ontologia intermedia utilizzata per rappresentare i punti di interesse. Questa sarà specializzata con una serie di ontologie calate sui singoli domini quali strutture ricettive, parcheggi, trasporto pubblico, farmacie, ecc. **Questa ontologia è da ritenersi stabile**
  + **ACCO (Strutture Ricettive - Accommodation Facilities- ACCO-AP_IT)  [DOC](https://w3id.org/italia/onto/ACCO)**: Ontologia del profilo applicativo italiano sulle strutture ricettive. **Questa ontologia è da ritenersi stabile**
  + **MU (Unità Di Misura - Measurement Unit - MU-AP_IT)  [DOC](https://w3id.org/italia/onto/MU)**: Ontologia di supporto per la modellazione delle unità di misura.**Questa ontologia potrebbe subire ancora modifiche. E' da ritenersi instabile**
  + **POT (Prezzi Offerte e Biglietti - Prices/Offers and Tickets - POT-AP_IT)  [DOC](https://w3id.org/italia/onto/POT)**: Ontologia del profilo applicativo italiano per i prezzi, le offerte i biglietti. E' un'ontologia di supporto che consente di rappresentare offerte, prezzi e biglietti. Essa può essere utilizzata in svariati contesti come per esempio nell'ambito dei luoghi ed eventi della cultura, nell'ambito delle strutture ricettive o nell'ambito del trasporto, ecc. **Questa ontologia è da ritenersi stabile**
  + **RO (Ruoli - Roles - RO-AP_IT)  [DOC](https://w3id.org/italia/onto/RO)**: Ontologia del profilo italiano per la specifica dei ruoli. **Questa ontologia è da ritenersi stabile**
  + **CPEV (Eventi Pubblici - Public Events - CPEV-AP_IT)  [DOC](https://w3id.org/italia/onto/CPEV)**: Ontologia del profilo applicativo italiano per la rappresentazione degli eventi pubblici (Core Public Event Vocabulary - Italian Application Profile). La versione 0.3 dell'ontologia è stata sviluppata considerando i risultati del gruppo europeo Core Public Event Vocabulary e in collaborazione con alcune PA locali (Comune di Palermo, Comune di Udine, Provincia Autonoma di Trento, OpenContent, CNR - Istituto per le Tecnologie Didattiche). **Questa ontologia è da ritenersi stabile**
  + **Park (Parcheggi - Car Parks - PARK-AP_IT)  [DOC](https://w3id.org/italia/onto/PARK)**: La terza versione dell'ontologia del profilo applicativo italiano per la rappresentazione dei dati sui parcheggi (Parking Italian Application Profile - Park-AP_IT) è più stabile e include anche la possibilità di specificare condizioni d'accesso ai parcheggi (inclusi orari d'apertura). **Questa ontologia è da ritenersi stabile**
  + **AccessCondition (Condizioni d'accesso - AC-AP_IT)  [DOC](https://w3id.org/italia/onto/AccessCondition)**: Ontologia del Profilo applicativo itailano per la rappresentazione di condizioni di accesso tipo orari di apertura, prenotazioni, chiusure. L'ontologia può essere usata per modellare le condizioni di accesso a luoghi, eventi e servizi pubblici. **Questa ontologia è da ritenersi stabile**
  + **Language (Lingue - Language-AP_IT) [DOC](https://w3id.org/italia/onto/Language)**: Ontologia del profilo italiano per la modellazione delle lingue. L'ontologia è di supporto. **Questa ontologia è da ritenersi stabile**
  + **CPSV (Core Public Service Vocabulary - CPSV-AP_IT) [DOC](https://w3id.org/italia/onto/CPSV)**: E' il profilo italiano del vocabolario europeo sui servizi pubblici. La versione qui fornita 1.1 è un aggiornamento della precedente versione pubblicata su dati.gov.it, rifattorizzata anche per poter integrarsi con tutte le altre ontologie della rete. L'ontologia è utilizzata anche nel catalogo servizi.gov.it **L'ontologia è da ritenersi stabile**.
  + **Cultural-ON [DOC](https://w3id.org/italia/onto/Cultural-ON)**: Ontologia sviluppata in collaborazione con il MIBACT. In questo repository è pubblicata la versione rifattorizzata per l'integrazione con tutte le altre ontologie della rete OntoPiA. **Questa versione è da ritenersi ancora instabile**
  + **Ontologia dei contratti pubblici (Public Contracts Ontology) [DOC](https://w3id.org/italia/onto/PublicContract)**. Pubblicata una prima versione dell'ontologia. La stessa è da **ritenersi INSTABILE**. Per ulteriori dettagli si consiglia di leggere il readme che accompagna l'ontologia stessa;
  + **ADMS (Asset Description Metadata Schema - Italian Application Profile - ADMS-AP_IT) [DOC](https://w3id.org/italia/onto/ADMS):**: Prima versione dell'ontologia di meta livello per descrivere asset semantici come le ontologie. Essa è basata sull'uso di DCAT-AP_IT e sullo standard ADMS e il suo profilo ADMS-AP definito nell'ambito del programma ISA della Commissione Europea. Questa ontologia è utilizzata per metadatare tutte le ontologie della network OntoPiA. **Questa ontologia è da ritenersi stabile**
  + **DCAT (DCAT-AP_IT - Italian Application Profile for metadata) [DOC](https://w3id.org/italia/onto/DCAT)**: Ontologia del profilo nazionale di metadatazione per i dati (aperti e non aperti). **Questa ontologia è da ritenersi stabile**
  + **(L0) (Livello 0 - Level0 - L0-AP_IT) [DOC](https://w3id.org/italia/onto/l0)**: E' un'ontologia top-level che consente di collegare tutte le ontologie sopra elencate abilitando così la rete di ontologie. **Questa ontologia è da ritenersi stabile**


I **Vocabolari Controllati** sono in generale disponibili in RDF (tipicamnete nelle tre serializzazioni RDF/Turtle, RDF/XML, JSON-LD), in CSV (codifica usata **UTF-8** con separatore **,** (comma)) e in excel. Nell'ambito del DAF, i vocabolari controllati sono dataset e come tali includono i relativi metadati conformi a DCAT-AP_IT.
In particolare, il contenuto della directory Vocabolari Controllati è attualmente il seguente:

  + **public-event-types (Tipi Eventi Pubblici)**: E' una classificazione dei possibili tipi di eventi pubblici. La classificazione è allineata a schema.org.
  + **licences (Licenze)**: E' la classificazione delle licenze, tipicamnte utilizzate nel contesto open data, suddivise per tipologia. Questo è il vocabolario controllato da utilizzare per il profilo di metadatazione nazionale DCAT-AP_IT.
  + **theme-subtheme-mapping (Mapping Temi-Sottotemi - Mapping DCAT-AP_IT Themes and Subthemes)**: E' il mapping tra i 13 temi del profilo DCAT-AP_IT e alcune voci del vocabolario Eurovoc da utilizzare per la proprietà [dct:subject](https://linee-guida-cataloghi-dati-profilo-dcat-ap-it.readthedocs.io/it/latest/dataset_elementi_raccomandati.html#sottotema-del-dataset-dct-subject) del profilo DCAT-AP_IT. Il mapping puà essere utilizzato anche in applicativi per guidare l'utente a selezionare i sottotemi Eurovoc in linea con i temi DCAT-AP_IT. Il mapping è basato principalmente sull'analogo mapping utilizzato dall'European Data Portal.
  + **territorial-classifications (Classificazione Territorio)**: Sono diversi dataset riguardanti la suddivisione territoriale. Al momento è stato pubblicato il vocabolario controllato sulle Regioni, sulle Province e sul Paese "Italia". **Sono in fase di produzione il vocabolario controllato che rappresenta l'archivio storico dei comuni e la classificazione ufficiale degli stati esteri.**
  + **poi-category-classification (Classificazione Categorie Punti di Interesse)**: E' un dataset delle categorie di punti di interesse. La categorizzazione è basata sul primo livello di classificazione dei punti di interesse offerta da Open Street Map.
  + **classifications-for-public-services (Classificazioni per i servizi pubblici)**: La directory contiene tutti i vocabolari controllati, ad esclusione di quelli già definiti a livello Europeo per cui si rimanda ai relativi riferimenti, attualmente utilizzati nello sviluppo del catalogo servizi pubblici.
  + **classifications-for-accommodation-facitilities (Classificazioni per le strutture ricettive**: La directory contiene tutti i vocabolari controllati specifici per le strutture ricettive. Al momento la directory contiene la classificazione a stelle e quella sulle tipologie; in quest'ultimo caso si sono tenute in considerazione anche alcune classificazioni disponibili a livello regionale.
  + **classifications-for-people (Classificazioni per le persone)**: La directory è strutturata in sotto directory relative al Genere delle Persone e ai Titoli di studio (o Grado di istruzione). Questi vocabolari sono stati sviluppati in collaborazione con ISTAT, come emerge dai relativi metadati DCAT-AP_IT.
  + **classifications-for-organizations (Classificazioni per le organizzazioni)**: La directory è strutturata in sotto directory relative alle Forme Giuridiche (legal-status), Ateco, Cofog e S13. Le classificazioni sono state predisposte in stretta collaborazione con ISTAT.
  + **classifications-for-culture (Classificazioni per il settore cultura)**: La directory è strutturata in sotto directory relative, al momento, ai soli ambiti disciplinari, che possono essere utilizzati nell'ambito dei luoghi ed eventi della cultura. E' stato predisposto un readme che spiega la creazione del vocabolario fatto in collaborazione con alcuni colleghi del MIBACT e la Sapienza Università di Roma.

**Ontologie in fase di sviluppo e non ancora pubblicate** (**Ontologies under development**):
  + **Ontologia GTFS**: l'ontologia utilizzata per modellare i dati del trasporto pubblico urbano statico che seguono la specifica GTFS.
