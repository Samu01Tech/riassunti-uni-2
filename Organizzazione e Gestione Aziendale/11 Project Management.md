# 11 - Project Management

## Definizioni

- programma: iniziativa a lungo termine, insieme di progetti

- progetto: insieme complesso di attività integrate, con budget e obiettivi, con inizio e fine in 3 anni max

- compito: sforzo a breve termine

![](C:\Users\Samu\AppData\Roaming\marktext\images\2023-04-03-08-40-14-image.png)

Il processo di **project management** ha come obiettivo ultimo il raggiungimento degli obiettivi strategici dell'organizzazione e la pianificazione/controllo dei progetti. Le fasi di p.m. quindi si dividono in **pianificazione** e **controllo**.

In un progetto le **variabili** sono i tempi, i costi, le risorse e le qualità.

## Gestione dei tempi

### Diagramma di GANTT

```mermaid
gantt
    dateFormat  YYYY-MM-DD
    title       Adding GANTT diagram functionality to mermaid
    excludes    weekends
    %% (`excludes` accepts specific dates in YYYY-MM-DD format, days of the week ("sunday") or "weekends", but not the word "weekdays".)

    section A section
    Completed task            :done,    des1, 2014-01-06,2014-01-08
    Active task               :active,  des2, 2014-01-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2              :         des4, after des3, 5d

    section Critical tasks
    Completed task in the critical line :crit, done, 2014-01-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :1d
    Functionality added                 :milestone, 2014-01-25, 0d

    section Documentation
    Describe gantt syntax               :active, a1, after des1, 3d
    Add gantt diagram to demo page      :after a1  , 20h
    Add another diagram to demo page    :doc1, after a1  , 48h

    section Last section
    Describe gantt syntax               :after doc1, 3d
    Add gantt diagram to demo page      :20h
    Add another diagram to demo page    :48h
```

## Gestione dei costi

- **BCWS** (Budget Cost of Work Scheduled) – costo pianificato

- **ACWP** (Actual Cost of Work Performed) – costo effettivamente sostenuto

- **BCWP** (Budget Cost of Work Performed) – valore delle attività realizzate fino a quel momento

## Gestione delle risorse

Si pensi allo schema di organizzazione a matrice (Capitolo 2).

Il **manager di funzione** assicura efficienza ed efficacia nella sua funzione.

Il **manager di progetto** si preoccupa di indirizzare le risorse per raggiungere gli obiettivi.

### Matrice RACI

Serve per assegnare le responsabilità. Responsible, Accountable (responsabile del responsabile, es Vice President Product), Consulted, Informed.

![](C:\Users\Samu\AppData\Roaming\marktext\images\2023-04-03-09-08-00-image.png)

### Project Manager

Il PM deve possedere abilità organizzative, gestionali e relazionali ed è la figura che individua, impegna e coordina 
le risorse al fine di conseguire gli obiettivi di costi e tempi (e qualità) del progetto. Aspetti chiave di un PM sono:

- avere una visione globale del progetto

- anticipare le richieste di mercato

- coordinare risorse

- essere una figura di leadership

- avere abilità di negoziazione

### Il Project Management Office (PMO)

Consiste in un'unità organizzativa che ha come obiettivo la direzione centralizzata e coordinata dei progetti di un'organizzazione. Assegna priorità e risorse.

# Luxottica Experience

## Who?

## Stakeholders

principalmente team esterni alla supply chain. I PM seguono end to end il progetto.

**New Product Introduction NPI**, 

BLM per monitorare il life cycle del prpodotto

model stock: scorte di emergenza per avere sempre materiale per la produzione

## Tasks

- 

- Portfolio management

- Project management
  
  - team leader, accountant, project manager

## a

process groups
