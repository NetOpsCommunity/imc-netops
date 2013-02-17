imc-netops
==========

Custom Scripts and adapters for HP's Intelligent Management Center (IMC)

These scripts have been contributed by members of www.netopscommunity.net. They are provided free of charge, but with NO GUARANTEE WHATSOEVER. These are not officially supported by HP. 

These scripts are intended to extend the capabilities of IMC, supporting devices that HP does not support out of the box. Core functions we hope to provide are for Configuration Backup and Resore. Anything else - software image management, VLAN management, etc - is a bonus.

If you have any problems with any scripts, post it at www.netopscommunity.net, and we'll try to help.

To use the scripts, copy the desired vendor folder from adapters/ICC to your IMC server. Install it at <IMC_INSTALL_DIR>/server/conf/adapters/ICC.

Note that the first time you install a new adapter, you will need to restart IMC. After that, you can make minor changes to the scripts, without restarting IMC.

If the sysObjectID is not currently known by IMC, you will also need to add the device model/series/vendor to IMC. Do this in the IMC GUI, at System -> Resource Management -> Device Model

You can also email lindsay.k.hill@gmail.com if you're having any problems.
