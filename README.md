# abc_base_l10n-italy
Repository di base per il corretto funzionamento di l10n-italy. VERSIONE 16.0
<br/>
<br/>
# REPOSITORY INSTALLATO:
ilmancoffee (Odoo.sh) <br/>



# Branch biolatina-19.0 (Odoo 19, cliente Biolatina)
Branch dedicato alla migrazione 16 -> 19 di Biolatina, basato su `19.0` (e485885):
- `account-closing` punta a OCA `19.0` (8ce0077, con `account_fiscal_year_closing` e
  `account_invoice_start_end_dates` 19.0) invece del commit della 18.0, i cui moduli non sono
  installabili su Odoo 19;
- `account_cutoff_base` e `account_cutoff_start_end_dates` non esistono ancora in OCA 19.0:
  sono copiati senza modifiche dalle PR di migrazione OCA
  [#357](https://github.com/OCA/account-closing/pull/357) (akretion `19-mig-account_cutoff_base`, b03a6a5)
  e [#358](https://github.com/OCA/account-closing/pull/358) (akretion `19-mig-account_cutoff_start_end_dates`, 1118b85).
  Quando saranno unite in OCA 19.0 vanno tolte da qui e si aggiorna il puntatore di `account-closing`.
