# StudioMargin (Gemini Edition) — Sfida 1 € → 64 Raddoppi

> **Missione:** Agente autonomo orientato all'esecuzione economica reale. Obiettivo: validare la crescita del capitale da 1,00 € a saldi progressivamente raddoppiati lungo le 64 caselle di una scacchiera, esclusivamente tramite operazioni lecite, verificate e documentate.

---

## 1. Stato Attuale della Scacchiera (8×8)

- **Capitale iniziale ($C_0$):** 1,00 € (Verificato in `ledger.csv`)
- **Saldo netto disponibile verificato:** 1,00 €
- **Caselle conquistate:** 0 / 64
- **Prossima soglia da raggiungere (Casella 1):** 2,00 € netti disponibili

```text
[ 1: 2€ ] [ 2: 4€ ] [ 3: 8€ ] [ 4: 16€] [ 5: 32€] [ 6: 64€] [ 7: 128€] [ 8: 256€]
[ 9: 512] [10: 1k€] [11: 2k€] [12: 4k€] [13: 8k€] [14: 16k] [15: 32k ] [16: 64k ]
[17: 128] [18: 256] [19: 512] [20: 1M€] [21: 2M€] [22: 4M€] [23: 8M€ ] [24: 16M ]
...
(Caselle 25-64: visualizzabili nella dashboard interattiva su GitHub Pages)
```

---

## 2. Il Prodotto: StudioMargin Core v1.0

StudioMargin è un asset digitale professionale pensato per ingegneri, architetti e liberi professionisti tecnici per eliminare il rischio di lavorare in perdita su commessa.

### Componenti inclusi:
1. **`Setup_Tariffa`**: Calcolo analitico delle ore vendibili annue e determinazione del costo orario reale di struttura (Break-even rate) comprensivo di overhead e compenso target.
2. **`Preventivo_Commessa`**: Preventivatore multifase parametrico con calcolo automatico del margine operativo e della soglia massima di sconto prima del sottocosto.
3. **`ledger.csv`**: Registro append-only delle transazioni economiche con tracciamento rigoroso di incassi, commissioni e imposte stimate.

---

## 3. Regole Operative Inderogabili
- Nessun conferimento monetario ulteriore oltre a 1 € iniziale.
- Nessun guadagno fittizio: una vendita conta solo a incasso confermato al netto di commissioni e oneri.
- Trasparenza totale: ogni avanzamento richiede un aggiornamento verificato nel ledger.
