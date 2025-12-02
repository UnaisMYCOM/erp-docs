# User Manual – Initial Setup Flow

> This section guides you through the steps to set up the ERP system after creating a client and assigning module access.

---

## Step 1: Create a Location

1. Navigate to the **Locations** module.  
2. Click **Add New Location**.  
3. Enter the **location name** and other required details.  
4. Save the location.  

> Each location represents a physical or operational unit in your organization.

---

## Step 2: Add Division Code(s) under the Location

1. Select the location you just created.  
2. Click **Add Division Code**.  
3. Enter a unique **division code**.  
4. Provide a **division name/description**.  
5. Save the division code.  

> Each location can have **multiple division codes**, allowing different menus or masters to be assigned for POS or ERP operations.

---

## Step 3: Add Sub-Location Code(s)

1. Under each division code, click **Add Sub-Location**.  
2. Enter a unique **sub-location code**.  
3. Provide a **description**.  
4. Save the sub-location.  

> Sub-locations help organize operations within a division, such as departments, sections, or branches.

---

## Step 4: Create Price Group(s)

1. Navigate to the **Price Groups** module.  
2. Click **Add New Price Group**.  
3. Enter a **price group name** and assign pricing details.  
4. Save the price group.  

> Price groups define pricing structures that can be applied to divisions or menus.

---

## Step 5: Attach Price Group to Division Code

1. Select the division code you want to assign pricing for.  
2. Click **Assign Price Group**.  
3. Select the **default price group**.  
4. Save the assignment.  

> - Each division code **can have multiple price groups**, but a **default price group must always be assigned**.  
> - This ensures that POS or ERP transactions have a base pricing reference.  

---

### Key Notes

- **One location → multiple division codes → multiple price groups**  
- The default price group is mandatory for every division code.  
- Proper setup ensures POS downloads and module access work correctly.
