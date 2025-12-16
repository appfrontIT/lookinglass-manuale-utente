# Quotation Blockers & Validations

### 1. Contact Data Already Used (Email / Phone)

When creating a quotation, the system checks that an email address and phone number are not already used by another customer within the same intermediary.

If the email or phone number is already linked to a different fiscal code, the quotation cannot be issued.

In this case, the system shows a blocking message such as:

* "Email già utilizzata dal codice fiscale \{{fiscal code\}}"
* "Telefono già utilizzato dal codice fiscale \{{fiscal code\}}"
* "Non sarà possibile emettere il preventivo senza cambiare associazione"

To continue, the user must correct the contact details or use the correct customer record.

Some intermediaries are allowed to reuse email addresses or phone numbers. For these intermediaries, the quotation is not blocked, but a warning message is shown before issuance. The user must confirm the warning in order to proceed. \
The contact data check happens during the **Personal Data** step (Page 3) and may also be shown again on the **Summary** page for confirmation.

### 2. Digital Signature Buttons

When a document is sent for a digital signature, the signing link is always sent directly to the customer by email. This ensures that the customer is the only person who can access and complete the signing process.

By default, intermediaries will only see the option to **send the email** to the customer. The buttons to open the signing page or copy the signing link are not shown to everyone.

For some authorised intermediaries, additional buttons may be visible. These allow opening the signing page or copying the signing link. This access is limited to ensure the signing process remains secure.
