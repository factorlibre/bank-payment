Create SEPA files for Direct Debit

Module to export direct debit payment orders in SEPA XML file format.

SEPA PAIN (PAyment INitiation) is the new european standard for
Customer-to-Bank payment instructions. This module implements SEPA Direct
Debit (SDD), more specifically PAIN versions 008.001.02, 008.001.03, 008.001.04 and
008.001.08. PAIN 008.001.08 is generated with the structured postal address of
both the creditor and the debtor (the address mode is configurable on the
payment method). It is part of the ISO 20022 standard, available on
http://www.iso20022.org.

The Implementation Guidelines for SEPA Direct Debit published by the European
Payments Council (http://http://www.europeanpaymentscouncil.eu) use PAIN
version 008.001.02. Version 008.001.08 is the default one in new installations.
If your bank does not support it yet, use version 008.001.02.
