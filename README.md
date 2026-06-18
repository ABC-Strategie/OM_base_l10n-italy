# abc_base_l10n-italy
Repository di base per il corretto funzionamento di l10n-italy. VERSIONE 16.0
<br/>
<br/>
# REPOSITORY INSTALLATO:
ilmancoffee (Odoo.sh) <br/>

## ⚠️ NOTA SOTTOMODULI FORKATI (Odoo 19)
Il sottomodulo `rest-framework` attualmente punta a un fork aziendale (`ABC-Strategie/OM_OCA_rest-framework`) anziché al repository originale OCA. 
Questo è stato reso necessario per correggere un bug bloccante su Odoo 19 (sostituzione di `users` con `user_ids` nel file `rest_log/security/groups.xml`). 
Quando OCA rilascerà la correzione ufficiale nel loro branch 19.0, il file `.gitmodules` andrà ripristinato all'URL originale.
