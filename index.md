# Practical Android

## Perchè l'ennesimo corso Android?
Benvenuto al corso di "practical android". Online ci sono milioni di tutorial sul mondo Android, tra cui uno offerto da 
Google stessa. Quindi perchè dovresti perdere tempo a leggere questo?

Essendo uno sviluppatore ormai da qualche anno, mi ritrovo a spesso ad andare a leggere tutorial su librerie, 
architettura, componenti Android, ma ho notato che la maggior parte della documentazione esistente ricopre:
- Come usare uno specifico tool;
- Come risolvere uno specifico problema;

Spesso è esattamente ciò che cerchi, ma molte volte non risponde alle domande più importanti:
- Sto utilizzando il tool giusto per risolvere questo problema?
- Quali sono i pro e i contro dell'adozione di questa tecnologia?

La risposta a queste domande è soggettiva, quindi ti ritroverai a leggere molti "dipende". Dipende dal contesto e dal 
tipo di applicazione che stai facendo, dal tipo di funzionalità, di come si svilupperà il progetto, \[...\]

## A chi è diretto?

Al momento questo corso è indirizzato a chiunque abbia dimestichezza con la programmazione. Non è necessario conoscere 
Kotlin: se conosci qualsiasi altro linguaggio di programmazione come Java, Php, Javascript, Python \[...\] hai già le 
basi per poter scrivere del codice Kotlin (if/else, loop, classi, ...).

Ad ogni modo, cercherò di dare una breve spiegazione, sempre tramite esempi, di tutte le feature di Kotlin che 
incontrerai lungo il percorso.

In futuro *potrei* estendere questo blog anche a tecnologie Kotlin.

## La struttura di questo corso

Dati i presupposti, in questa guida non troverai tutto ciò che ti serve per creare un'app Android. Come ho già detto, ci 
sono milioni di corsi e guide online che rispondono alle tue domande. Il mio obiettivo è quello di creare un'app e, man 
mano che saranno necessari nuovi concetti, li introdurrò in maniera rapida e superficiale. Sta a te poi approfondire 
quelle che sono le tematiche più interessanti.

Potrebbe sembrare un approccio semplicistico, ma questo ti permette di avere una visione olistica della piattaforma per 
comprendere come funziona, i punti di forza e debolezza e le aree che vanno approfondite.

## Esempio pratico
Ecco un piccolo assaggio: quando si lavora con tecnologie object oriented (come Java, Kotlin, ...) è necessario 
istanziare i componenti. 
Per farlo puoi utilizzare varie tecniche: Factory/Service Locator, la libreria _Koin_ o la libreria _Hilt_ 
di Google basata su <em>Dagger</em>. Potrei scrivere decine e decine di post su come configurare _Dagger_ o _Koin_, ma 
tutte queste informazioni le troverai sulle pagine ufficiali delle librerie o su blog post su medium. 
Quindi, quello che farò sarà:
1. Implementare una prima soluzione manuale usando il pattern Service Locator;
2. Effettuare un refactoring del codice usando _Koin_;
3. Effettuare un secondo refactoring del codice usando _Hilt;_
4. Analizzare pro e contro dei tre approcci visti sopra;

Alla fine di questa sezione, avrai abbastanza elementi per decidere in autonomia quale approccio utilizzare nel tuo 
progetto e quale degli elementi sopra citati vorrai studiare in maniera più approfondita e consapevole.

[Prossimo: Indice del corso](index_of_content.md)