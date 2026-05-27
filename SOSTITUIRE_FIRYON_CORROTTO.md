# ⚠️ Da fare: sostituire Firyon-corrotto

Nello slider di Firyon (sezione "I Quattro Dei"), la versione **corrotta** è attualmente un **placeholder generato automaticamente** (un filtro lavico applicato a Firyon sano).

## Perché
Il file su Google Drive (`Firyon_Dio del fuoco_Cattivo_1.jpeg`, ID `1mC3Eri5I7VSQOu_Ni38WXrmvGxYrf8u0`) è un JPEG già compresso e piccolo: il connettore Drive lo restituisce in un formato che, in questa sessione, non sono riuscito a salvare su file. Per non bloccare il completamento della pagina ho generato un derivato dal Firyon sano con un effetto lava/fuoco coerente col lore (Colosso di lava).

## Come sostituirlo (3 modi, scegli il più semplice)

### Opzione A — Dal tuo PC (più veloce)
1. Scarica il file da Drive (cartella Personaggi): `Firyon_Dio del fuoco_Cattivo_1.jpeg`.
2. Aprilo in qualsiasi editor (Foto/Anteprima/Paint.NET/GIMP) ed esportalo come JPG.
3. Ridimensiona così che il lato lungo sia ~1000 px, qualità 86 circa.
4. Salvalo come `assets/img/firyon_corrotto.jpg` SOSTITUENDO il file attualmente nel repository.
5. Carica su GitHub → Vercel ridistribuirà.

### Opzione B — Caricalo nella prossima chat
Trascina semplicemente quel singolo file nella prossima conversazione e ti ottimizzo + sostituisco io.

### Opzione C — Tieni il placeholder
Funziona graficamente (il Colosso di lava è effettivamente rosso/incandescente). Per la presentazione orale potrebbe bastare. Decidi tu.

## Dove si trova nel codice
`personaggi.html`, sezione `<div class="god fuoco right">`, attributo `data-corrupt="assets/img/firyon_corrotto.jpg"` (riferimenti già pronti, basta sostituire il file).
