# Modelli e Processi nell'Ingegneria del Software

> L’ingegneria del software è l’istituzione e l’impego di principi ingegneristici ben fondati, allo scopo di ottenere in modo economico software affidabile ed efficiente

> Più che una disciplina o insieme di conoscenze, è un modo di affrontare un problema

> (1) applicazione di una strategia sistematica, disciplinata e misurabile allo sviluppo, esercizio e manutenzione del software; (2) studio di strategie di cui al punto (1)

L'ingegneria del software si occupa di:

- Planning

- Analysis

- Design

- Programming

- Implementation

- Development

- Testing

- V&V

Il **processo** di creazione di un software utilizza **metodi**, tramite **strumenti**. In tutto il processo particolare attenzione è alla **qualità**.

## Modelli

1. Modello a **cascata**: il modello a cascata è un approccio sequenziale alla creazione di software in cui ogni fase del processo viene completata prima di passare alla successiva. Le fasi includono l'analisi dei requisiti, la progettazione, lo sviluppo, i test e la manutenzione.

2. **Processo incrementale**: questo modello prevede lo sviluppo del software in modo incrementale, in cui il prodotto finale viene costruito in diverse fasi. Ad ogni fase, viene aggiunto funzionalità al software, in modo che alla fine sia completo.

3. Modello **prototipale**: questo modello prevede la creazione di prototipi del software, in modo da poter testare l'idea e verificare se funziona come previsto. Questo approccio può essere utile in situazioni in cui i requisiti non sono ancora ben definiti.

4. Modello a **spirale**: questo modello prevede lo sviluppo del software in modo iterativo, in cui ogni iterazione passa attraverso quattro fasi: pianificazione, analisi dei rischi, sviluppo e valutazione.

5. Modello a **componenti**: questo modello prevede l'uso di componenti predefinite per costruire il software. In questo modo, i componenti possono essere riutilizzati in diversi progetti, riducendo il tempo di sviluppo complessivo e aumentando la produttività.

## Service Oriented Architecture (SOA)

È un paradigma architetturale per la progettazione e lo sviluppo di software. Il sistema si compone di servizi autonomi, indipendenti e modulari, richiamabili da una interfaccia standard. Ciò favorisce la creazione di sistemi software che sono più flessibili, scalabili, interoperabili e riutilizzabili.

## Model Driven Development (MDD)

Il Model Driven Development (MDD) è un approccio alla creazione di software che si basa sulla creazione di modelli software come il nucleo della progettazione, produzione e manutenzione del software. In MDD, il modello è il documento di progetto principale, che rappresenta il software in un formato astratto, indipendente dalla piattaforma di destinazione. In esso vengono usati linguaggi come l'UML. Il software che ne esce è più efficiente e di qualità. 

## Approccio o Metodo Agile

La metodologia Agile è un approccio alla gestione del progetto che si concentra sulla flessibilità, l'adattabilità e la collaborazione tra team di lavoro. Si basa su valori come la comunicazione continua, la risposta ai cambiamenti, la consegna continua e la soddisfazione del cliente. La metodologia Agile può essere applicata sia a una SOA che agli altri modelli.

### Documentazione

Mettendo a confronto una metodologia tradizionale a cascata e una metodoloogia Agile, si nota come la prima abbia una curva molto più ripida nella scrittura della documentazione, in quanto richiesta dal metodo in se. UNa metodoloogia Agile invece cresce gradualmente insieme al progetto aveendo una leggera crescita nel finale. 

## Applicazioni dell'Agile

### Scrum

Scrum è un framework specifico di progettazione software. Si basa su un approccio iterativo e incrementale, il lavoro è organizzato in sprint di breve durata. Il **Product Owner** definisce e controlla il **backlog**, ovevro il lavoro da fare.

### Extreme Programming (XP)

XP è una metodologia di sviluppo software Agile che si concentra sulla produzione di software di alta qualità e sulla massimizzazione della soddisfazione del cliente.

XP è composto da una serie di pratiche di sviluppo software, come:

- **testing automatizzato** - vengono scritti test pria ancora di inziare lo sviluppo

- **programmazione a coppie** - due programmatori lavorano sullo stesso computer per ridurre errori

- l'integrazione continua (**CI**) - piccole aggiunte di codice ogni volta

- **refactoring** - riscrittura del codice in maniera più pulita

Queste pratiche sono progettate per migliorare la qualità del software e ridurre il rischio di errori e di fallimenti del progetto.

Il planning fa uso di **user stories** che descrivono le funzionalità del software richieste dal cliente. Ciascuna ha un "costo" che si traduce in tempo da dedicargli.

Gli **unit test** mettono alla prova le singole user stories.

## DevOps

Sempre più spesso i software vengono installati in grandi e complesse infrastrutture. È necessario coordinare gli sviluppatori (Dev) con chi gestisce l'infrastruttura (Ops). 

## Modularizzazione e microservizi

È una architettura adatta per lo sviluppo di grandi applicazioni e chhe sfrutta il cloud, evoluzione delle SOA. 
