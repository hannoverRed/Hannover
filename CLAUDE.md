# DEXTER Dashboard — Projektregeln

## Dateinamen & Template-Name bei Änderungen

Bei jeder Änderung an einem Dashboard-Flow immer:
1. **Template-Name** im JSON (`data[0].name`) auf neue Version setzen, z.B.:
   - `DEXTER Dashboard v2.3.01 - cleaned`
   - `DEXTER Dashboard v2.3.02 - fix xyz`
2. **Dateiname** entsprechend anpassen, z.B.:
   - `flowsDEXTER_Dashboard_v2.3.01__cleaned.json`
   - `flowsDEXTER_Dashboard_v2.3.02__fix-xyz.json`

Versionsnummer-Schema: `vMAJOR.MINOR.PATCH` — Patch hochzählen bei kleinen Änderungen/Fixes.
