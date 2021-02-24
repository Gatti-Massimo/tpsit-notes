--- 
title: "Diagramma di Attività"
description: "Inserisci un sottotitolo qui" # aggiorna testo !
date: 2021-02-15T21:43:46+01:00 # aggiorna data !

draft: true # cambia con false quando viene approvata la versone definitiva !

languageName: "Italiano"
author: ["Massimo", "Riccardo", "Gabriele", "Francesco"] 

tags: ["Requisiti Software"]   
categories: ["Requisiti Software"]   
---  

<!-- Write content Down Here :) -->

# Activity Diagram - ITA

## Cos'è un Activity diagram?

L'Activity Diagram è un una tipologia di diagramma UML utilizzato per descrivere gli aspetti dinamici del sistema. Un Activity Diagram è essenzialmente una versione avanzata del Flowchart che modella il flusso da un'attività a un'altra attività.

## Quando utilizzare gli Activity diagram?

I diagrammi delle attività servono per la modellazione di workflow, per descrivere processi con una forte componente di computazione parallela oppure per rappresentare la logica interna di un processo di qualunque livello.

È anche adatto per modellare il modo in cui una raccolta di casi d'uso si coordina per rappresentare i flussi di lavoro aziendali.

- Identifica i casi d'uso dei candidati, attraverso l'esame dei flussi di lavoro aziendali
- Identificare le condizioni preliminari e successive (il contesto) per i casi d'uso
- Modella i flussi di lavoro tra / all'interno dei casi d'uso
- Modella flussi di lavoro complessi nelle operazioni sugli oggetti
- Modella in dettaglio attività complesse in un Activity Diagram di alto livello

## Differenza tra un Activity diagram e un Flowchart

I Flow Chart sono stati inventati prima degli activity diagram.

I non programmatori utilizzano i Flow Chart per modellare i workflows, ad esempio un produttore utilizza un Flow Chart per spiegare e illustrare come viene prodotto un determinato prodotto.

Possiamo chiamare un Flowchart una versione primitiva di un Activity Diagram, i processi aziendali in cui è coinvolto il processo decisionale vengono espressi utilizzando un Flowchart.

## Costruzione

Gli Activity Diagram sono costituiti da una serie di forme collegate con frecce.

I tipi di forma più importanti:

- Le ellissi, rappresentano le azioni;
- I diamanti, rappresentano le decisioni;
- Le barre nere rappresentano l'inizio (divisione) o la fine (unione) di attività concorrenti;
- Un cerchio nero rappresenta l'inizio (nodo iniziale) del Flowchart;
- Un cerchio nero circondato rappresenta la fine (nodo finale).
- Le frecce vanno dall'inizio alla fine e rappresentano l'ordine in cui si svolgono le attività.

## Struttura di un Activity diagram

![Activity%20Diagram%20-%20ENG%206aa4b6c2df1043ab800dde8c0093faff/1.png](Activity%20Diagram%20-%20ENG%206aa4b6c2df1043ab800dde8c0093faff/1.png)

## Esercizio di esempio:

Activity Diagram di un elaboratore di testi.

L'esempio di Activity Diagram riportato di seguito descrive il flusso di lavoro di un processo testuale per creare un documento attraverso i seguenti passaggi:

- Apri Office Suite.
- Crea un file.
- Salva il file con un nome univoco all'interno di una directory.
- Componi il contenuto del documento.
- Se un'interfaccia grafica è richiesta aprire un programma apposito, realizzala e inseriscila nel documento.
- Se è necessario lo spreadsheet , apri il package dello spreadsheet , crea lo spreadsheet e infine incollalo nel documento.
- Salva il file.
- Stampa una copia cartacea del documento.
- Esci da Office Suite.

## Grafico d'Esempio:

![Activity%20Diagram%20-%20ENG%206aa4b6c2df1043ab800dde8c0093faff/2.png](Activity%20Diagram%20-%20ENG%206aa4b6c2df1043ab800dde8c0093faff/2.png)





