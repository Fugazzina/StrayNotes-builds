# StrayNotes — da installare

Qui ci sono le versioni di **StrayNotes** pronte da installare, compilate da Codemagic.
Il codice dell'app sta in un altro repository (privato).

| | iPhone (SideStore) | Android (Obtainium) |
|---|---|---|
| **StrayNotes** | ramo [`ios`](../../tree/ios) | Release **Android** |
| **StrayNotes Test** | ramo [`ios-test`](../../tree/ios-test) | Release **Android Test** |

StrayNotes Test è la versione di prova: si installa accanto a quella normale, con i suoi dati,
e ha l'icona col bollino **T**.

## iPhone, con SideStore

In SideStore: **Sources › +** e incolla l'indirizzo.

- StrayNotes: `https://raw.githubusercontent.com/Fugazzina/StrayNotes-builds/ios/source.json`
- StrayNotes Test: `https://raw.githubusercontent.com/Fugazzina/StrayNotes-builds/ios-test/source.json`

Poi **Browse › StrayNotes › Free**. Gli aggiornamenti compaiono in **My Apps**.

## Android, con Obtainium

In Obtainium: **Add App** e come URL `https://github.com/Fugazzina/StrayNotes-builds`.
Prima di premere *Add*, apri le opzioni del sorgente GitHub:

- StrayNotes: *Filter release titles by regular expression* → `^Android$`
- StrayNotes Test: *Filter release titles by regular expression* → `^Android Test$`

Per avere tutte e due, aggiungi l'indirizzo due volte, una per filtro.
L'APK è firmato sempre con la stessa chiave: gli aggiornamenti si installano sopra senza perdere i dati.
