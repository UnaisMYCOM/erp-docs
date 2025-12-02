```markdown
# Price Group (Master)

Short description
-----------------

Price Groups define groups of customers, items, or channels that share price rules, discounts, or special pricing tiers. They enable flexible pricing strategies across customer segments and item categories.

Navigation
----------

- Menu: Masters → Price Group
- Permission: masters.pricegroup.view / masters.pricegroup.manage

Key Fields
----------

| Field | Type | Required | Description |
|---|---:|:---:|---|
| Price Group Code | Text | Yes | Unique short identifier for the price group |
| Name | Text | Yes | Descriptive name for the price group |
| Applies To | Picklist | Yes | Customer / Item / Channel / Location |
| Discount Type | Picklist | No | Percentage / Fixed Amount / Tiered |
| Effective From | Date | No | Start date for the pricing rule |
| Effective To | Date | No | End date for the pricing rule |
| Active | Boolean | Yes | Enables or disables the price group |

Common Actions
--------------

- Create / Edit price group definitions
- Assign customers, items or locations to a price group
- Bulk import price tiers and conditions

Business Rules & Notes
----------------------

- A customer or item may belong to multiple price groups; precedence rules govern which group applies.
- Effective dates are used to apply time-bound promotions or contracts.

Examples
--------

- "VIP" → Priority customers with 10% discount
- "WHOLESALE-STD" → Wholesale pricing for bulk buyers

Related
-------

- Sales → Price lists and discount rules
- Masters → Location, Division (for scoped pricing strategies)

---

_Last updated: 2025-12-02_
```
