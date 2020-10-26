# Misure minime di sicurezza informatica per la P.A. (AGID)

Le misure minime di sicurezza ICT emanate dall’AgID, sono un riferimento pratico per valutare e migliorare il livello di sicurezza informatica delle amministrazioni, al fine di contrastare le minacce informatiche più frequenti.

Le misure consistono in controlli di natura **tecnologica, organizzativa e procedurale** e utili alle Amministrazioni per valutare il proprio livello di sicurezza informatica.

A seconda della complessità del sistema informativo a cui si riferiscono e della realtà organizzativa dell’Amministrazione, le misure minime possono essere implementate in modo graduale seguendo **tre livelli di attuazione.**

1. **Minimo**: è quello al quale ogni Pubblica Amministrazione, indipendentemente dalla sua natura e dimensione, deve necessariamente essere o rendersi conforme.
2. **Standard**: è il livello, superiore al livello minimo, che ogni amministrazione deve considerare come base di riferimento in termini di sicurezza e rappresenta la maggior parte delle realtà della PA italiana.
3. **Avanzato**: deve essere adottato dalle organizzazioni maggiormente esposte a rischi (ad esempio per la criticità delle informazioni trattate o dei servizi erogati), ma anche visto come obiettivo di miglioramento da parte di tutte le altre organizzazioni.

## Normativa di Riferimento

CIRCOLARE 18 aprile 2017 , n. 2/2017 . Agenzia per L'italia Digitale

[vedi Gazzetta Ufficiale](https://cert-agid.gov.it/download/CircolareAgID_170418_n_2_2017_Mis_minime_sicurezza_ICT_PA-GU-103-050517-2.pdf)

L’adeguamento alle misure minime è a cura del responsabile della struttura per l'organizzazione, l'innovazione e le tecnologie, come indicato nel CAD (art. 17 ) o, in sua assenza, del dirigente designato. Il dirigente responsabile dell'attuazione deve compilare e firmare digitalmente il "Modulo di implementazione" allegato alla Circolare 18 aprile 2017, n. 2/2017.

Secondo la circolare, le misure minime di sicurezza devono essere adottate da parte di tutte le pubbliche Amministrazioni entro il 31 dicembre 2017.

Sito istituzionale di riferimento: https://www.agid.gov.it/it/sicurezza/misure-minime-sicurezza-ict 

## Controlli di Sicurezza 

Le misure minime di sicurezza prevedono un insieme di controlli denominato ABSC (Agid Basic Security Control(s)). I controlli ABSC sono un sottoinsime dei controlli del SANS 20,  pubblicato dal Center for Internet Security come CCSC «[CIS Critical Security Controls for Effective Cyber Defense](https://www.cisecurity.org/controls/)». 

La scelta del sottoinsieme dei controlli è così illustrata nella circolare:

> La scelta di prendere le mosse dall’insieme di controlli noto come SANS 20, oggi pubblicato dal Center for Internet Security come CCSC «CIS Critical Security Controls for Effective Cyber Defense» nella versione 6.0 di ottobre 2015, trova giustificazione, oltre che nella larga diffusione ed utilizzo pratico, dal fatto che esso nasce con una particolare sensibilità per i costi di vario genere che l’implementazione di una misura di sicurezza richiede, ed i benefi ci che per contro è in grado di offrire. L’elenco dei venti controlli in cui esso si articola, normalmente riferiti come Critical Security Control (CSC), è ordinato sulla base dell’impatto sulla sicurezza dei sistemi; per cui ciascun controllo precede tutti quelli la cui implementazione innalza il livello di sicurezza in misura inferiore alla sua. È comune convinzione che i primi cinque controlli siano quelli indispensabili assicurare il minimo livello di protezione nella maggior parte delle situazioni e da questi si è partiti per stabilire le misure minime di sicurezza per la pubblica amministrazione italiana, avendo ben presente le enormi differenze di dimensioni, mandato, tipologie di informazioni gestite, esposizione al rischio, e quant’altro caratterizza le oltre ventimila amministrazioni pubbliche.
>
>  Occorre inoltre osservare che il CCSC è stato concepito essenzialmente nell’ottica di prevenire e contrastare gli attacchi cibernetici, ragione per la quale non viene data particolare rilevanza agli eventi di sicurezza dovuti a casualità quali guasti ed eventi naturali. Per questa ragione, ai controlli delle prime cinque classi si è deciso di aggiungere quelli della CSC8, relativa alle difese contro i malware, della CSC10, relativa alle copie di sicurezza, unico strumento in grado di proteggere sempre e comunque le informazioni dal rischio di perdita, e della CSC13, riferita alla protezione dei dati rilevanti contro i rischi di esfiltrazione.



Per facilitare l'implementazione i ABSC controlli sono identificati da un codice coerente con quello originale CCSC. Ciascun CSC è costituito da una famiglia di misure di dettaglio più fine, che possono essere adottate in modo indipendente. Nei controlli ABSC  è stato introdotto un ulteriore terzo livello, nel quale la misura di secondo livello viene decomposta in misure elementari, ancora una volta implementabili in modo indipendente. 

> Pertanto un ABSC è identifi cato da un identificatore gerarchico a tre livelli x, y, z, dove x e y sono i numeri che identificano il CSC concettualmente corrispondente e z individua ciascuno dei controlli di livello 3 in cui questo è stato raffinato. Al primo livello, che corrisponde ad una famiglia di controlli destinati al perseguimento del medesimo obiettivo, è associata una tabella che li contiene tutti. 

L'elenco dei controlli è descritto in formato tabellare nel modulo di implementazione. Nella terza colonna delle tabelle è riportato l'identificativo della sottocategoria del «FNSC» (Framework nazionale di sicurezza cibernetica) a cui il controllo è riconducibile

- [Modulo di Implementazione (formato DOC)](https://cert-agid.gov.it/download/MM.doc)
- [Modulo di Implementazione (formato DOCX)](https://cert-agid.gov.it/download/MM.docx)
- [Modulo di Implementazione (formato ODT)](https://cert-agid.gov.it/download/MM.odt)
- [Modulo di Implementazione (formato RTF)](https://cert-agid.gov.it/download/MM.rtf)



  Le ultime tre colonne sono booleane e costituiscono una linea guida che indica quali controlli dovrebbero essere implementati per ottenere un determinato livello di sicurezza ( «Minimo», «Standard», oppure «Alto») 

### Elenco dei controlli ABSC/CSC

1. ABSC1 (CSC1) INVENTARIO DEI DISPOSITIVI AUTORIZZATI 
2. ABSC2 (CSC2) INVENTARIO DEI SOFTWARE AUTORIZZATI E NON AUTORIZZATI 
3. ABSC3 (CSC3) PROTEGGERE LE CONFIGURAZIONI DI HARDWARE E SOFTWARE SUI DISPOSITIVI MOBILI, LAPTOP, WORKSTATION E SERVER 
4. ABSC4 (CSC4) VALUTAZIONE E CORREZIONE CONTINUA DELLA VULNERABILITÀ 
5. ABSC5 (CSC5) USO APPROPRIATO DEI PRIVILEGI DI AMMINISTRATORE 
6. ABSC8 (CSC8) DIFESE CONTRO I MALWARE 
7. ABSC10 (CSC10) COPIE DI SICUREZZA 
8. ABSC13 (CSC13) PROTEZIONE DEI DATI 