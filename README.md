# aged_users
Powershell script to retrieve user account details from Azure Entra and list (and possibly disable) all user accounts that have no recorded login within the last x number of days.

Configure $TenantID for the current Azure Tenant
Configure $OlderThanDays for the number of days an account must be dormant for before it will be disabled


