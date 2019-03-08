About
---------

Roles and Resource Service driver base package.


What's New
-----------------
4.7.0
- NetIQ Identity Manager 4.7 release
- New configuration parameter to decide whether to make Role and Resource driver as multi-threaded or not.
- New mapping table "NOVLRSERVB-MultiThreadedDisjointDataSetMappingTable" added to define the disjoint problem set formulti-threaded Role and Resource driver.
- Added new rule to the policy "NOVLRSERVB-sub-etp" to decide the disjoint set and append this information in the driver command.
- Added new action in the rule "Convert the event into a custom command to send to the driver" in the policy "NOVLRSERVB-sub-etp" to add the Group Membership changes the driver command.
- Added new action in the rule  "Convert the event into a custom command to send to the driver" in the policy "NOVLRSERVB-sub-etp" to add event id in the driver command.
- Added the driver configuration to set the maximum number of commands in the driver storage.
- Added changes to handle rename event.
- Added changes to handle moving user to different container event.
- Added configuration for selective logger and dynamic group member resync
- Corrected the description of driver configuration's.

4.6.0
- NetIQ Identity Manager 4.6 release
- New configuration parameter to control parallelization of role-resource assignment operations.
- Removed unused attribute "nrfAssignedResources" from the filter to improve performance.

4.5.0
- NetIQ Identity Manager 4.5 release
- Addition of a gcv-ref 'service-account-dn' on driver parameters. If the resource request was initiated by this dn, any approvals or provisioning workflows associated with the resource are bypassed. 

2.0.0
- Novell Identity Manager 4.0.2 release
- Addition of nrfStatus to nrfRole objectClass on RRSD driver filter

1.0.0
- Novell Identity Manager 4.0 ISO release