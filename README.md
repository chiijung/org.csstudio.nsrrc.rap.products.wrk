# Control System Studio RAP products
######################################## Created By Author ########################################
Repository contains products definitions for the CS-Studio RAP products. It includes:  
- Web OPI: BOY runner (org.csstudio.opibuilder.rap.product)  
- Web Data Browser: Archive viewer based on BEAUtY (org.csstudio.trends.databrowser2.rap.product)  
- Web Alarm: BEAST Alarm Viewer (org.csstudio.alarm.beast.ui.rap.product)  

All products depend on the [cs-studio](https://github.com/ControlSystemStudio/cs-studio). In order to build the war products you need to provide a p2 repository that contains all plugins. By default it will try to fetch them from the [css update site](http://download.controlsystemstudio.org/updates/<ver>). If you want to use cs-studio plugins that are newer than the on on the p2 repository, make sure that they are available in your local repository (i.e. if you edited a plugin in the cs-studio/applications, install that plugin into the local maven repository using the **mvn clean install** command inside that plugin).

To build the RAP products execute command **mvn clean verify**. If the operation was completed successfully the war products will be located in the **wars** folder.
########################################
#
# All Rap products of NSRRC. Any modification is welcomed. Thanks.
