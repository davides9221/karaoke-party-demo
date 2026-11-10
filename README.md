# Karaoke Party — Demo e app per il telefono

Download ufficiale della **versione demo gratuita** di Karaoke Party e
dell'app Android **Karaoke Party Telefono**.

> Karaoke Party è un software **proprietario a codice chiuso**: il codice
> sorgente non è distribuito. La versione **Pro** e **Davide Karaoke Studio**
> non sono disponibili pubblicamente; per informazioni:
> <https://davides9221.it>

## Scarica l'ultima versione

| Cosa | File | Requisiti |
|------|------|-----------|
| **Karaoke Party — Demo** (Windows) | [Karaoke.Party.Demo.1.1.1.zip](https://github.com/davides9221/karaoke-party-demo/releases/latest/download/Karaoke.Party.Demo.1.1.1.zip) | Windows 10/11 |
| **Karaoke Party Telefono** (Android) | [Karaoke.Party.Telefono.apk](https://github.com/davides9221/karaoke-party-demo/releases/latest/download/Karaoke.Party.Telefono.apk) | Android 8 o successivo |

Tutti i file sono anche nella pagina
[Releases](https://github.com/davides9221/karaoke-party-demo/releases/latest),
con le note di versione e i checksum SHA-256.

### Karaoke Party — Demo (Windows)

1. Scarica `Karaoke.Party.Demo.1.1.1.zip` e estrailo in una cartella.
2. Avvia `Karaoke Party Demo.exe`, tenendo la cartella `assets` accanto
   all'eseguibile (contiene il soundfont del sintetizzatore interno).
3. Apri un brano dal menu **File** o dal pannello **Archivio**.
4. Per MP3+G servono la coppia `.mp3` + `.cdg` con lo stesso nome.

La demo funziona **gratuitamente per 30 giorni** dal primo avvio. Alla scadenza
il programma mostra la schermata di licenza e blocca la riproduzione. Lo stato
della prova è protetto: viene conservato in copie nascoste in
`%APPDATA%\KaraokeParty`, `%LOCALAPPDATA%\KaraokeParty` e in alcune chiavi del
registro di Windows. Cancellare i file di stato **non** fa ripartire i 30
giorni.

La demo non ha altre limitazioni: suona i brani MIDI/KAR con il sintetizzatore
interno, apre le basi MP3+G, mostra i testi sincronizzati ed è compatibile con
i microfoni Wi-Fi.

### Karaoke Party Telefono (Android)

L'app trasforma il telefono in **microfono** e **leggio**: manda la voce al
player via Wi-Fi e mostra il testo sullo schermo. Fino a quattro telefoni
possono cantare insieme.

1. Installa `Karaoke.Party.Telefono.apk` sul telefono (Android 8 o successivo).
2. Collega telefono e PC alla **stessa rete Wi-Fi**.
3. Sul player premi **MIC**: la finestra mostra l'indirizzo del PC; inseriscilo
   nell'app (oppure usa **CERCA**).
4. Ogni telefono compare nella finestra MIC con il suo vuometro.

La voce viaggia solo sulla rete di casa: nessun server, nessun cloud.

## Requisiti

- **Windows 10/11** a 64 bit per il player.
- Una porta MIDI di uscita **oppure** il sintetizzatore interno (incluso nel
  pacchetto demo, tramite il soundfont GeneralUser GS).
- **Android 8 o successivo** per l'app del telefono.
- Se il player non si avvia, installa il
  [Microsoft Visual C++ Redistributable x64](https://aka.ms/vs/17/release/vc_redist.x64.exe).

## Cosa contiene il pacchetto demo

```
Karaoke Party Demo.exe
LEGGIMI.txt
LICENZA.txt
LICENSE-EN.txt
assets\logo.png
assets\soundfont.sf2
assets\GeneralUser-GS-LICENSE.txt
assets\rustysynth-LICENSE.txt
```

## Note

- L'eseguibile **non è firmato digitalmente**: al primo avvio Windows
  SmartScreen può chiedere di confermare. Scegli **Ulteriori informazioni** →
  **Esegui comunque**.
- Scarica solo da questa pagina o dal sito ufficiale. Non sono distribuite
  versioni modificate.
- La versione **Pro** di Karaoke Party e **Davide Karaoke Studio** non sono
  pubblicate qui: sono software a licenza, legati al singolo computer.

## Licenza

**Software proprietario a codice chiuso — tutti i diritti riservati.**
La versione demo può essere usata gratuitamente per 30 giorni e il pacchetto
ufficiale non modificato può essere ridistribuito gratuitamente. La versione
Pro e Davide Karaoke Studio richiedono una chiave di licenza emessa
dall'autore.

Testo completo: [`LICENSE`](LICENSE) (inglese) e [`LICENSE-IT`](LICENSE-IT)
(italiano). I componenti di terzi (rustysynth, GeneralUser GS, modelli AI)
mantengono le proprie licenze, incluse nel pacchetto.

© 2026 Davide (davides9221) — <https://davides9221.it>
