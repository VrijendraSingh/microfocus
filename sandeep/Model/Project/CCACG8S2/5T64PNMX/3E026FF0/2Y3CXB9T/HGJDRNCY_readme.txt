About
---------

LDAP driver base package.


What's New
-----------------
-2.3.0
- Localization support

2.2.0
-Internal bug fixes(#896647 )
Bug 896647 -  Security fix added. Keystore password configuration type is changed to password-ref from string.

2.1.0
- Internal bug fixes (#812828) 
Bug 812828 - LDAP configuration option "Maximum number of operations for a single bind" in wrong hive:-Updated the Upgrade Settings for the package so that it picks the value from the previous version 
of package.
(NOTE-Downgrading back to the prior version will result in multiple values in publisher and driver options.You will need to remove the definition from publisher options in initial settings manually after downgrade although even without this driver will work fine.)

2.0.0
- Internal bug fixes (#758994, #755180, #754884)

1.0.0
- Novell Identity Manager 4.0 ISO release
