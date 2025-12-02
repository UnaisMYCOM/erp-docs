```markdown
# Division (Master)

Short description
-----------------

The Division master groups business units or organizational segments within the company. Divisions are used for reporting, permissions, and to control master data visibility. Examples include "Retail", "Wholesale", "Services", or geographic divisions.

Navigation
----------

- Menu: Masters → Division
- Permission: masters.division.view / masters.division.manage

Key Fields
----------

| Field | Type | Required | Description |
|---|---:|:---:|---|
| Division Code | Text | Yes | Short unique code for the division |
| Name | Text | Yes | Full name of the division |
| Description | Long Text | No | Free-text description of the division |
| Parent Division | Reference | No | Optional parent to create a hierarchy |
| Default Currency | Picklist | No | Default functional currency for the division |
| Active | Boolean | Yes | Enable or disable the division |

Common Actions
--------------

- Create / Edit / Deactivate divisions
- Assign default settings or policies specific to a division

Business Rules & Notes
----------------------

- Division code must be unique within the company.
- Divisions can be used to filter reports and control data access.
- When deleting a division, reassign dependent entities (customers, vendors, locations) first.

Examples
--------

- "RTAIL" → Retail Division
- "INTL" → International Sales Division

Related
-------

- Masters → Location
- Finance → Cost Centers and GL mappings

---

_Last updated: 2025-12-02_
```
