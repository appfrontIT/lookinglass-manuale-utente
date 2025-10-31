# Policy Management (EN)

## Policy Management Procedure

### Access and Visibility (Scoping)

Lookinglass ensures that users can only access data relevant to their organizational scope.\
Each user’s access to policies and financial documents (_titoli_) is determined by:

* **Company affiliation**: Users can see only policies and _titoli_ belonging to their company.
* **Permission-based scoping**: If granted, users can also access data from **sub-companies** (e.g., branches, agencies).
* **Role-based operations**: Actions such as editing, printing, issuing, or cancelling are only visible if the user’s role includes the corresponding permissions.

This scoping system guarantees security and operational segregation between different entities in the distribution chain.

***

### Policy Overview

Each policy in Lookinglass is a full representation of the insured contract. It contains:

* The complete dataset collected during the quotation process: vehicle, personal, contract, and pricing information.
* ATR (Attestato di Rischio) details and Bersani declarations.
* Link to any _titoli_ (accounting records) connected to the policy.
* Uploads of all required documentation.
* Current and historical statuses: issued, suspended, cancelled, reactivated, etc.
* PDF generation available at any time.

A policy becomes immutable once issued and must go through controlled procedures for any subsequent modification.

***

### Post-Sale Operations (Policy Lifecycle Management)

#### Replacement (Sostituzione Polizza)

Replacement creates a **new policy** based on an existing one. It is used in cases such as:

* Errors in personal or vehicle data discovered after issuance
* Change of vehicle due to demolition or sale (when ATR recovery is not performed)
* Change of insured vehicle while maintaining the same policyholder

Replacement can be triggered from the policy list or directly from the policy detail page. The workflow replicates the steps of policy issuance:

* The user can edit key fields (license plate, address, etc.)
* Supporting documents (new registration, new address certificate) must be uploaded
* The _Adequacy Questionnaire_ does **not** need to be completed again

**Business Logic Constraints:**

* A policy **cannot** be replaced on the same day it was issued
* The original _titolo_ must be valid and paid
* Replacement results in a new policy with a new ID; the old policy is automatically closed\


**Additional Notes for WAKAM Policies**

For **WAKAM** policies, replacements now automatically keep certain parameters from the previous policy to ensure pricing consistency:

* The **ATRC Level** (a coefficient used to calculate premiums) remains the same as in the former policy
* The **intermediary** cannot be changed during a replacement
* The **region** may change; in that case, the pricing template will adapt accordingly
* Changing the **Fiscal Code** does not affect the quotation price
* If specific ownership or ATR options are modified, the premium may change accordingly

***

#### Cancellation (Annullamento Polizza)

Cancellation permanently terminates a policy and updates the financial records accordingly.

Valid reasons include:

* **Theft**: Requires a police report
* **Right of withdrawal**: Only valid within 14 days for web/phone contracts; for intermediated contracts, company discretion applies
* **Sale**: Requires proof of sale
* **Demolition**: Requires scrapping certificate
* **Exportation**: Requires proof of circulation termination

Cancellation is initiated via the action column in the policy table. The user must:

* Select a reason from the dropdown
* Upload the corresponding documentation
* Confirm cancellation

Once confirmed:

* The platform redirects the user to _Titoli_
* A new _titolo_ is generated to mark the cancellation
* The operation finalizes when the user clicks the confirmation button

***

#### Suspension (Sospensione Polizza)

A policy can be suspended temporarily to stop coverage and defer future installments.

Conditions for suspension:

* **No unpaid installments**: Suspension is blocked if any _titolo_ is unpaid or overdue
* **Timing restriction**: Suspension cannot be requested on the same day as an installment due date; it must be the day before or after

The first suspension is free of charge. Additional suspensions may incur a cost.

To suspend a policy:

* Click the corresponding icon in the action column
* Select the reason and suspension date
* Upload any required documentation
* Submit the request

A corresponding _titolo_ is updated to reflect the suspension state.

***

#### Reactivation (Riattivazione Polizza)

Reactivation resumes a suspended policy.

The process is nearly identical to suspension:

* Click the reactivation icon in the action column
* Select the reactivation date and upload supporting documents
* Complete the submission

A new _titolo_ is generated, and the user must specify the reason for reactivation. The system validates that:

* The policy is currently suspended
* Any prior unpaid installments have been resolved

***

### Titoli: Financial Operations and State Tracking

_Titoli_ are the financial components associated with each policy. They record:

* **Installments and payment flows**: cash-in, installments, fractions
* **State transitions**: issuance, suspension, cancellation, reactivation
* **Justifications and metadata**: reason for change, user who performed the action, and timestamps

The _titolo_ module supports:

* **Cashing a policy**: Registers a payment and activates coverage
* **Cancelling a policy**: Processes premium refund if due
* **Paying or recovering installments**: Cashing future or pending _titoli_

Any action on a policy triggers a synchronized update on the related _titolo_, ensuring a consistent and auditable workflow.

***

### Additional Business Logic Checks

The platform enforces strict business logic to prevent inconsistent actions. Examples include:

| Operation        | Blocked If...                                    |
| ---------------- | ------------------------------------------------ |
| **Replacement**  | Same-day issue OR unpaid _titolo_                |
| **Suspension**   | Pending installments OR request on due date      |
| **Cancellation** | Missing required documentation                   |
| **Reactivation** | Not in suspended state OR prior debts unresolved |

***

### Summary

Policy management in Lookinglass is designed to ensure traceability, correctness, and alignment between commercial and financial records. Thanks to role-based access and strict logic enforcement, each action follows a secure and auditable process.
