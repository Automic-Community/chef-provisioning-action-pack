## Getting Started:


###### Description

This actions can be used to control chef. The available functions enables you to provision a new host with chef and control this process from the release manager.
Additionally cookbooks and recipes are available to install the automic agent and service manager and create or update deployment targets.
		
###### Actions

1. Chef Bootstrap
2. Chef Get Node Attribute
3. Chef Run List Add
4. Chef Run List Check
5. Chef Set Node Attribute
6. Run Chef Client

		
###### Compatibility:

1. Oracle JRE 1.7 or later
2. Docker 1.12 or later on Linux or Windows
3. The Agent must be able to access the Docker daemon in order to make HTTP(s) requests

###### Prerequisite:

1. Automation Engine should be installed.
2. Automic Package Manager should be installed.

###### Steps to install action pack source code:

1. Clone the code to your machine.
2. Go to the package directory.
3. Run the command apm upload in the directory which contains package.yml (source/):
   Ex. **apm upload -force -u <Name>/<Department> -c <Client-id> -H <Host> -pw <Password> -S AUTOMIC -y -ia -ru**


###### Package/Action Documentation

Please refer to the link for [package documentation](source/ae/DOCUMENTATION/PCK.AUTOMIC_CHEF.PUB.DOC.xml)

###### Third party licenses:

The third-party library and license document reference.[Third party licenses](source/ae/DOCUMENTATION/PCK.AUTOMIC_CHEF.PUB.LICENSES.xml)

###### Useful References

1. [About Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_AboutPacksandPlugins.htm?Highlight=Action%20packs)
2. [Working with Packs and Plug-ins](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#PluginManager/PM_WorkingWith.htm#link10)
3. [Actions and Action Packs](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#_Common/ReleaseHighlights/RH_Plugin_PackageManager.htm?Highlight=Action%20packs)
4. [PACKS Compatibility Mode](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#AWA/Variables/UC_CLIENT_SETTINGS/UC_CLIENT_PACKS_COMPATIBILITY_MODE.htm?Highlight=Action%20packs)
5. [Working with actions](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/AB_WorkingWith.htm#link4)
6. [Installing and Configuring the Action Builder](https://docs.automic.com/documentation/webhelp/english/AA/12.3/DOCU/12.3/Automic%20Automation%20Guides/help.htm#ActionBuilder/install_configure_plugins_AB.htm?Highlight=Action%20packs)

###### Distribution: 

In the distribution process, we can download the existing or updated action package from the Automation Engine by using the apm build command.
Example: **apm build -y -H AE_HOST -c 106 -u TEST/TEST -pw password -d /directory/ -o zip -v action_pack_name**
			
			
###### Copyright and License: 

Broadcom does not support, maintain or warrant Solutions, Templates, Actions and any other content published on the Community and is subject to Broadcom Community [Terms and Conditions](https://community.broadcom.com/termsandconditions)

###### Questions or Need Help? 

Join the [Automic Community Integrations](https://community.broadcom.com/communities/community-home?CommunityKey=83e49dd4-b93e-464a-a343-2bb1e51c13ec) to discuss this integration.
