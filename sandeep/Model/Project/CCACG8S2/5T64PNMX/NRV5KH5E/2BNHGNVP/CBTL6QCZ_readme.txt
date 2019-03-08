About
---------

User Application driver base package.


What's New
-----------------
4.7
- New system entity "sys-nr-user-group-categories" & changes on another system entity sys-delegator
- Package changes with additional system resources & system resource category for Helpdesk feature.
- Added dependency on Email Based Approval and Helpdesk ticket notification templates packages 
- New resource attributes to filter for Resource Expiration
- Additional attributes added to Resource system entity for resource expiration, CPRS
- Additional attribute on User to take care of dashboard preferences

4.5.1
- Fix for resources deleted by Access Review still appear in Catalog Admin/Provisioning Dashboard.

4.5.0
- Novell Identity Manager 4.5 release
- Added a new GCV "allow-fetch-named-passwords" to turn on fetching of named passwords over LDAP in workflows.
- Strip EntitlementRef attributes from syncing on permissions.


3.0
- New Entities, Navigation items and updates to all PRDs for the enhanced User Application UI. 

2.3.0
- Updates to the Roles, Resources and SoD PRDs to support the changes for IDM Approval Mobile App. 

2.2.0
- Novell Identity Manager 4.0.2 release
- UA Package Version synced with User Application version
- Added updated localized strings
- Updates to Roles Approval PRD
- Updates to DAL User Entity 
- Updates to NOVLUABASE-sub-etp-ManageModify to use entitlement purge type from a GCV instead of hardcoded values (Bug 704521).

1.0.6
- Entitlement Purge Type made as GCV

1.0.2
- Novell Identity Manager 4.0 FCS (via online update) release
- Added updated localized strings (Bug 644755)

1.0.1
- Novell Identity Manager 4.0 ISO release


Package Change Log
------------------------------------------
2/8/11 9:38 PM    Created new package version '1.0.4' from package 'User Application Base' (version = '1.0.3')

- Changed Application Version to 2.1 (Capricorn)
- Driver Version is set to 4.0.1

Package Change Log
------------------------------------------
3/22/12 11:47 AM    Created new package version '2.2.0.20120322114733' from package 'User Application Base' (version = '2.2.0')
3/22/12 3:02 PM    Sync'd object 'NOVLUABASE-sub-etp-ManageModify' (association id = 'B69NIKX3_201006281545170610') to package 'User Application Base' (version='2.2.0.20120322114733').



Package Change Log
------------------------------------------------
3/14/13 7:37 PM    Created new package version '2.3.0.20130322140334' from package 'User Application Base' (version = ''2.2.0.20120322114733')


---Updated the Roles, Resources and SoD PRDs to support the changes for IDM Approval Mobile App. 


Package Change Log
------------------------------------------
5/16/13 6:10 PM    Created new package version '3.0.0.20130516180959' from package 'User Application Base' (version = '3.0.0.20130516014750')
5/16/13 6:32 PM    Built release of package 'User Application Base' (version='3.0.0.20130516183235') at 20130516183235.
5/16/13 6:34 PM    Built release of package 'User Application Base' (version='3.0.0.20130516183406') at 20130516183406.


Package Change Log
------------------------------------------------
9/19/17 1:00 PM    Created new package version '4.7.0.20170919130037' from package 'User Application Base' (version = '4.7.0.20170911224118')
