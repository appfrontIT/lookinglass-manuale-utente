# Domain management

### Domain Management System (Gestione Domini)

The **Domain Management System** allows Lookinglass to manage access and visibility across multiple company environments.\
Each company or intermediary (for example, **WAKAM**, **DALLBOGG**, or **DAS**) operates under its own domain, ensuring that users can only access data belonging to their organization.

***

#### Purpose

The domain system was introduced to separate users, companies, and data across different business entities operating within the same Looking Glass environment.

* Each **domain** represents a company or intermediary’s unique environment (e.g.  `dalbog.ipagency.it`).
* This ensures that users registered under one company cannot access another company’s domain or data.
* Access control is automatic and enforced at login.

***

#### How It Works

1. **Domain Definition**
   * Each domain corresponds to a web address (e.g., `lookinglass.ipagency.it` or `wakam.ipagency.it`).
   * Only **Super Admins** from IPA can create, edit, or delete domains.
   * Each domain is linked to one or more companies.
2. **Company Association**
   * A company can have **multiple domains**.
   * A domain can also be shared by **multiple companies** (for example, intermediaries belonging to the same main group).
   * When creating or editing a company, authorized users can add or remove associated domains.
3. **Access Control**
   * When a user logs in, the system checks whether their company is linked to the domain they’re trying to access.
   * If the domain is **not authorized** for their company, login is denied with a clear message.
   * This prevents cross-domain access between different intermediaries.

***

#### Default Domain

* The first default domain is `lookinglass.ipagency.it`.
* When new companies are created, they are automatically assigned to the **same domain as their parent company**.
* If a company has no parent (top-level), only a Super Admin can choose the domain.

***

#### Permissions

* **Super Admins**: full access to create, edit, and remove domains.
* **Regular Admins**: can view and assign existing domains to their companies (if permitted).
* **Regular Users**: cannot view or modify domains.

***

#### Example Scenario

* **WAKAM** operates under domain `wakam.ipagency.it` and has intermediary code **935**.
* Several sub-companies (intermediaries) work under WAKAM’s domain.
* A user created under **DALLBOGG** (`dallbogg.ipagency.it`) cannot log in through the **WAKAM** domain.
* This ensures strict separation between environments and prevents unauthorized cross-company access.
