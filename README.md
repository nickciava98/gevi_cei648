GEVI CEI-64-8
=============

Descrizione
-----------
Aggiunto al sistema Gevi basato su Odoo 9.0 CE di ICOVER SpA il 
supporto a impianti di Messa a Terra CEI 64/8.

Requisiti
---------
* Implementazione del verbale di verifica periodica/straordinaria 
per impianti di Messa a Terra relativi alla normativa CEI 64/8.
* Cambio dell’intestazione presente sui report con l’aggiornamento 
della forma societaria in SpA (non piu` Srl).
* Miglioramento di alcuni menu dell’interfaccia grafica per semplificare 
la ricerca nelle varie categorie di impianto e nei vari contratti.

Utilizzo
--------
La modifica si integra totalmente con il sistema e il riscontro visivo 
è il medesimo degli impianti di Messa a Terra, così come richiesto.
Il nuovo report Verbale è visibile nella stampa del verbale associato. 
Funzionalmente l’utilizzo è esattamente lo stesso degli impianti di MAT, 
di conseguenza a livello logico può essere spiegato attraverso l’utilizzo 
degli insiemi:
* Insieme MAT il quale contiene tutti gli impianti di Messa a Terra e CEI-64-8.
* Sottoinsieme Messa a Terra di MAT, il quale contiene solo gli impianti di 
Messa a Terra escludendo i CEI-64-8.
* Sottoinsieme CEI-64-8 di MAT, il quale contiene solo gli impianti CEI- 64-8 
escludendo i Messa a Terra.

Autore
------
* Niccolò Ciavarella <niccolo.ciavarella@email.com>

Crediti
-------
* Claudio Salvi, Evotec Srl <claudio.salvi@evotec.biz>
* Antonio Longo <alongo@outlook.it>
