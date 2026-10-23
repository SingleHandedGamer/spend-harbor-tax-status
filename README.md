# Spend Harbor tax status

Public freshness notices for Spend Harbor's bundled, offline tax references.

- [Readable status](status-summary.json)
- [Signed app status](status.json)
- [Public verification key](public-key.json)

The app source, tax-rule library, monitoring code, source-review fingerprints and maintenance queue remain private. No personal or financial information is stored here. Phones fetch the same public notice; they do not send budgets or create maintenance alerts.

"Not configured" means that jurisdiction's monitoring sources have not been registered. "Review needed" means a source changed or an initial baseline needs review; it does not certify a tax-law change. "Last verified" is a historical review date, not a guarantee that the rules are current. Registry entries do not imply a working tax calculator. Reviewed rule changes will ship with app releases.

The signed file is for app verification; the readable file is for inspection. The public key is not a secret and cannot sign updates. Only the key pinned in the app establishes trust.
