About
---------

Delimited Text driver base package.


What's New
-----------------
2.3.1

-New enum field "Suppress Encrypted Attribute in Trace:" included under the driver parameters of driver settings
  Selecting "Yes" will  supress the Encrypted Attribute content.
 

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------
2.3.0

-New enum field "Add header to output file:" included under the subscriber options of driver parameters.
  Selecting "Yes" will add the xml declaration <?xml version="1.0" encoding="UTF-8" standalone="no" ?> to output xml file.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2.2.0 

-New GCV 'driver.association.attribute' added.
-Any attribute from among the field-names specified in Driver options can be selected as an association attribute.

Note: Email is currently used as an association attribute.

-The NOVLDTXTBASE-ots stylesheet has been modified to reduce customization effort.No further changes are required to maintain field orders on updating the Field-names under driver parameter.

Note:If you want to preserve your old field-names on upgrading to this package,you may have to re-enter the old values when prompted and proceed next.
         Currently because of designer limitation(#808304) , during upgrade the field-names revert back to default values.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2.1.0

- Internal Bug Fix(#514603)
- TAB as field delimiter usage:- Represent {tab} under the Field Delimiter option.
-The {tab} field delimiter functionality works with the latest Delimited shim version 4.0.0.

Note:   If you want to preserve your old field delimiter settings when you upgrade to this package version,you may have to re- enter your old field delimiter when prompted and  proceed  next.
            Currently because of the Designer limitation (Internal Bug #808304) , during the upgrade the field-delimiter reverts back to default value of comma(,)


-Internal Bug Fix(#809177)
-NOVLDTXTBASE-ots stylesheet modified to allow <query> documents to be passed to driver shim.
 -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2.0.0
- Internal Bug Fixes(#758405, #754884, #759077)

1.0.0
- Novell Identity Manager 4.0 ISO release.