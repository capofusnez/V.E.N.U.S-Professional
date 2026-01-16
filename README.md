# V.E.N.U.S-Professional


*******************************************************************************
    __      ________ _   _ _    _  _____ 
    \ \    / /  ____| \ | | |  | |/ ____|
     \ \  / /| |__  |  \| | |  | | (___  
      \ \/ / |  __| | . ` | |  | |\___ \ 
       \  /  | |____| |\  | |__| |____) |
        \/   |______|_| \_|_ \____/|_____/ 
                                           
            VENETA ENGINEERING NETWORK UTILITY SYSTEM
*******************************************************************************
 DOCUMENTO TECNICO STORICO E MANUALE OPERATIVO (Full Release)
*******************************************************************************
 Stato Software:  PROD (Production Ready)
 Versione:        3.2.5 "Professional" (LTS)
 Roadmap Target:  3.5.0 "Enterprise"
 Sviluppo:        Veneta Finishing S.r.l. - IT/Engineering Dept.
 Build Date:      2026.01.16
*******************************************************************************

1. LINEA DEL TEMPO E VERSIONAMENTO (EVOLUTION LOG)
-------------------------------------------------------------------------------
 [V 0.0] - GENESIS (Settembre 2025)
 - Proof of Concept: Script base per test automazione file-system.
 - Definizione della struttura ad albero delle commesse standard.

 [V 1.0] - CORE ENGINE (Ottobre 2025)
 - Rilascio della prima interfaccia testuale (CLI).
 - Implementazione logica di creazione directory su drive locali.

 [V 2.0] - GUI ADOPTION (Novembre 2025)
 - Passaggio a WinForms: Prima interfaccia grafica a finestre.
 - Supporto per unità di rete mappate e archivi NAS centralizzati.

 [V 3.0] - THE DARK SUITE (Gennaio 2026)
 - Rivoluzione estetica: Lancio del design "VENUS Dark Mode".
 - Integrazione componenti grafici Oro/Grigio e angoli arrotondati.
 - Introduzione del sistema di protezione Hardware ID (UUID).

 [V 3.1.0] - CLONE & SECURITY (12 Gennaio 2026)
 - Evoluzione logica: Passaggio alla clonazione speculare del contenuto.
 - Gestione privilegi: Copia dei file con elevazione per evitare blocchi NAS.
 - Feature: La cartella Modello viene ora processata prima dell'anno fiscale.

 [V 3.1.5] - SMART WORKFLOW (14 Gennaio 2026)
 - Migrazione Standard: Cambio separatore commessa da punto [.] a trattino [-].
 - Smart Prefix: Il numero commessa rimane persistente durante l'editing.
 - Config Sync: License e Config file posizionati accanto all'eseguibile.

 [V 3.2.0] - SYSTEM RESILIENCE (16 Gennaio 2026)
 - Data Segregation: Spostamento di Licenza e Configurazione in %LOCALAPPDATA%.
 - Independent Path: Il software non dipende più dalla cartella di avvio.
 - Anti-Ghost: Risolto bug cartelle nascoste post-creazione su server Linux.

 [V 3.2.5] - OTA UPDATE SYSTEM (RELEASE ATTUALE)
 - Over-The-Air Update: Implementato sistema di auto-aggiornamento via GitHub.
 - Dual-Sync: Aggiornamento simultaneo e forzato di Eseguibile e Note.
 - Admin Bypass: Lo script di update richiede privilegi elevati solo se necessario.
 - Edit List: Editor integrato nelle impostazioni per le liste cartelle.

2. LOGICA DI SICUREZZA E LICENZE CORPORATE
-------------------------------------------------------------------------------
 Il software adotta protocolli di sicurezza per la protezione del workflow:

 > LICENZA: Sistema "Node-Locked" vincolato univocamente al ComputerID.
 > ARCHIVIAZIONE: I file critici sono segregati nella cartella di sistema:
   %LOCALAPPDATA%/VENUS_System (per evitare cancellazioni accidentali).
 > PRIVACY: Validazione locale tramite hashing MD5. Nessun dato inviato esternamente.

3. ARCHITETTURA TECNICA (STABILITÀ & PRIVILEGI)
-------------------------------------------------------------------------------
 - ENGINE: Algoritmo di replica speculare ad alte prestazioni (Robocopy).
 - INTEGRITÀ: Copia integrale del contenuto del Modello (senza duplicare la root).
 - GESTIONE NAS: Script di post-creazione con 'attrib' per forzare la visibilità.
 - EREDITARIETÀ: Sincronizzazione automatica dei permessi NTFS dal Modello.

4. ROADMAP SVILUPPO (FUTURE DEVELOPMENTS)
-------------------------------------------------------------------------------
 [V 3.3.0] - PDF REPORTER: Generazione automatica scheda commessa.
 [V 3.4.0] - MULTI-TEMPLATE: Supporto per diversi settori aziendali.
 [V 3.5.0] - ENTERPRISE DASHBOARD: Integrazione database SQL.

5. MANUALE OPERATIVO DETTAGLIATO (USER GUIDE V3.2.5)
-------------------------------------------------------------------------------
 FASE A: PREPARAZIONE
 1. Configurare i percorsi NAS e Modello tramite l'icona Ingranaggio.
 2. Inserire la licenza se richiesto (ID PC visibile nell'area Info).

 FASE B: INSERIMENTO DATI
 1. Selezionare l'anno: il sistema calcolerà il primo progressivo [AA-NN] libero.
 2. Cliccare nel campo testo: il prefisso rimarrà fisso, digitare il cliente.

 FASE C: CREAZIONE
 1. Selezionare le sottocartelle tecniche e amministrative.
 2. Cliccare "CREA COMMESSA". Il sistema copierà il contenuto del modello
    e aprirà automaticamente la cartella in Esplora Risorse.

*******************************************************************************
   (c) 2026 VENETA FINISHING S.R.L. - TUTTI I DIRITTI RISERVATI
*******************************************************************************
