```markdown
# Location (Master)

Short description
-----------------

The Location master defines physical or logical sites used in the ERP system — for example warehouses, stores, manufacturing sites, or office locations. It centralizes address and inventory-handling settings that are referenced by transactions in Inventory, Sales, and Purchase modules.

Navigation
----------

- Menu: Masters → Location
- Permission: masters.location.view / masters.location.manage

Key Fields
----------

| Field | Type | Required | Description |
|---|---:|:---:|---|
| Location Code | Text | Yes | Unique short code identifying the location |
| Name | Text | Yes | Full name of the location |
| Type | Picklist | Yes | Warehouse / Store / Office / Production / Other |
| Address | Long Text | No | Mailing and physical address for the location |
| Country | Picklist | No | Country for address and tax/locale rules |
| Default Bin | Text | No | Default storage bin used for receipts/putaways |
| Active | Boolean | Yes | Enables or disables the location for transactions |

Common Actions
--------------

- Create / Edit / Deactivate locations
- Set default handling rules (receipts, putaways) per location
- Search and bulk import via CSV

Business Rules & Notes
----------------------

- Location codes must be unique across the company.
- Deactivating a location prevents new transactions but does not automatically change historical records.
- Locations that contain stock cannot be removed; transfer or zero-out stock first.

Examples
--------

- "WH-SYD" → Sydney Warehouse (type: Warehouse)
- "STORE-001" → Retail Store #1 (type: Store)

Related
-------

- Inventory → Warehouse / Bin setup
- Masters → Division (for grouping of locations)
- Masters → Price Group (for price rules per location groups)

---

_Last updated: 2025-12-02_
```
