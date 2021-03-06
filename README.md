[![Build Status](https://travis-ci.org/OCA/bank-statement-import.svg?branch=9.0)](https://travis-ci.org/OCA/bank-statement-import)
[![Coverage Status](https://coveralls.io/repos/OCA/bank-statement-import/badge.svg?branch=9.0)](https://coveralls.io/r/OCA/bank-statement-import?branch=9.0)

OCA bank statement import modules for Odoo
==========================================

This repository hosts:
* a 9.0 backport of the account_bank_statement_import modules from the master branch
* additionnal parsers and import features inspired by v7.0 branch from https://github.com/OCA/bank-payment and https://github.com/OCA/bank-statement-reconcile

[//]: # (addons)
Unported addons
---------------
addon | version | summary
--- | --- | ---
[account_bank_statement_import_base](account_bank_statement_import_base/) | 8.0.1.0.1 (unported) | Account Bank Statement Import
[account_bank_statement_import_camt](account_bank_statement_import_camt/) | 8.0.0.3.0 (unported) | CAMT Format Bank Statements Import
[account_bank_statement_import_mt940_base](account_bank_statement_import_mt940_base/) | 8.0.1.1.0 (unported) | MT940 Bank Statements Import
[account_bank_statement_import_mt940_nl_ing](account_bank_statement_import_mt940_nl_ing/) | 8.0.0.3.0 (unported) | MT940 IBAN ING Format Bank Statements Import
[account_bank_statement_import_mt940_nl_rabo](account_bank_statement_import_mt940_nl_rabo/) | 8.0.1.1.0 (unported) | MT940 import for dutch Rabobank
[account_bank_statement_import_ofx](account_bank_statement_import_ofx/) | 8.0.1.0.0 (unported) | Import OFX Bank Statement
[account_bank_statement_import_qif](account_bank_statement_import_qif/) | 8.0.1.0.0 (unported) | Import QIF Bank Statement
[account_bank_statement_import_save_file](account_bank_statement_import_save_file/) | 8.0.1.0.0 (unported) | Keep imported bank statements as raw data
[base_bank_account_number_unique](base_bank_account_number_unique/) | 8.0.1.0.0 (unported) | Enforce uniqueness on bank accounts

[//]: # (end addons)

Translation Status
------------------
[![Transifex Status](https://www.transifex.com/projects/p/OCA-bank-statement-import-9-0/chart/image_png)](https://www.transifex.com/projects/p/OCA-bank-statement-import-9-0)

----

OCA, or the Odoo Community Association, is a nonprofit organization whose 
mission is to support the collaborative development of Odoo features and 
promote its widespread use.

http://odoo-community.org/
