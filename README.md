# whmcs-credit-invoice

A simple module that allows admins to credit / refund invoices.

The module adds buttons to the WHMCS invoice edit page. You can refund an invoice
and easily navigate between a it's credit note.

The module does this by duplicating an invoice, setting it's status to "Paid",
and then inverting all the amounts to negative. Finally it adds some data to both
the original invoice admin notes as well as the credit notes admin notes, this is
to be able to easily keep track of which credit note belongs to which invoice, and vise-versa.
