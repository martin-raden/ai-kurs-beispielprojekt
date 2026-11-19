# Transaktionsdatensatz

Die Datei [`datensatz.csv`](datensatz.csv) enthält fünf beispielhafte
Transaktionen. Die Werte sind durch Kommas getrennt.

## Spalten

| Column | Description |
|---|---|
| `Date` | Transaction date in the format `DD.MM.YYYY` |
| `TransactionID` | Unique transaction identifier |
| `Currency` | Currency of the amount, for example `EUR`, `USD`, or `GBP` |
| `Amount` | Transaction amount with two decimal places and a decimal point |
| `Description` | Short description of the transaction |

## Enthaltene Daten

Die Datensätze umfassen Transaktionen vom 22. bis zum 25. Oktober 2023.
Es gibt fünf Transaktionen mit den IDs `TXN001` bis `TXN005`. Die Beträge
liegen zwischen `75.20` und `250.50`; verwendet werden die Währungen `EUR`,
`USD` und `GBP`.

| Datum | TransaktionsID | Währung | Betrag | Beschreibung |
|---|---|---|---:|---|
| 22.10.2023 | TXN001 | EUR | 100.00 | Einkauf im Supermarkt |
| 23.10.2023 | TXN002 | USD | 250.50 | Online-Kauf |
| 23.10.2023 | TXN003 | EUR | 75.20 | Restaurantbesuch |
| 24.10.2023 | TXN004 | GBP | 150.00 | Buchung im Hotel |
| 25.10.2023 | TXN005 | EUR | 200.00 | Autoreparatur |
