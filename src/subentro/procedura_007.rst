Procedura 007. Anomalia in scheda anagrafica
=================================================================

In quanto segue si riporta la procedura suggerita ai Comuni per la gestione delle anomalie: 

- EF004 - Progressivo ordine già assegnato ad altro soggetto della scheda famiglia/convivenza
- EF008 - Intestatario della scheda famiglia/convivenza assente
- EF010 - Scheda famiglia senza alcun soggetto associato


Precondizione
^^^^^^^^^^^^^
Per dare seguito alla presente procedura è necessario che l'ufficiale d'anagrafe disponga dell'accesso al sistema gestionale del Comune (APR o AIRE locale) con diritti di lettura e aggiornamento delle schede soggetto/famiglia/convivenza.

.. Important::
	Si evidenzia che l'ufficiale d'anagrafe ha la necessità di **lavorare in stretta sinergia con il proprio fornitore** per dare seguito alle necessarie attività di correzione delle anomalie.


Diagramma della procedura
^^^^^^^^^^^^^^^^^^^^^^^^^
La seguente figura sintetizza la procedura per la gestione delle anomalie.

.. image:: image/IMAGE_007.png


Descrizione azione
^^^^^^^^^^^^^^^^^^
In quanto segue si riporta una descrizione delle azioni previsti per la presente procedura.

AZIONE 007_001 - VERIFICA
-------------------------
L'ufficiale d'anagrafe verifica i dati relativi alla scheda famiglia/convivenza interessata dall'errore sul sistema gestionale del Comune (APR o AIRE locale) con l'obiettivo di constatare che i dati inoltrati al sistema ANPR coincidono con quelli registrati.

AZIONE 007_002 – NUOVO INOLTRO
------------------------------
Poiché i dati inoltrati al sistema ANPR non coincidono con quelli presenti nel sistema gestionale del Comune (probabilmente per problemi nella procedura di estrazione e predisposizione dei file di subentro utilizzata) è necessario provvedere nuovamente all'estrazione dei dati e alla predisposizione dei file di subentro al fine di provvedere ad eseguire l'inoltro al sistema ANPR.

AZIONE 007_003 – CONSOLIDAMENTO SCHEDA
--------------------------------------
L'ufficiale di anagrafe provvede a consolidare i dati relativi alla scheda famiglia/convivenza con errori, assicurando in particolare che:
- per la scheda famiglia/convivenza esista un unico intestatario;
- tutte le schede famiglia abbiano almeno un componente;
- il progressivo ordine dei soggetti in una scheda famiglia/convivenza non è duplicato.

AZIONE 007_004 - AGGIORNAMENTO E NUOVO INOLTRO
----------------------------------------------
L'ufficiale di anagrafe, sulla base del consolidamento effettuato, provvede ad aggironare la *schede famiglia* / *schede convivenza* sul sistema gestionale del Comune o ad assicurare la corretta transcodifica nella procedura di estrazione e predisposizione dei file di subentro, per dare seguito ad una nuova estrazione dei dati e alla predisposizione dei file di subentro al fine di provvedere ad eseguire l'inoltro al sistema ANPR.
