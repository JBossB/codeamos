 how to install Developer Studio 3.9.x.


Download Developer Studio.
Run the installer for your platform.
Select your Java runtime.
Select the directory to install Developer Studio. 
Choose whether you would like to install Command Line Tools or not. If so:
Select a product to init a Liferay Workspace
If selecting the Liferay DXP product, then browse to your activation key. 
Select if you would like to config a proxy for Blade or not. The proxy settings will be saved to Blade and jpm in the .jpm folder. 
Select if you would like to config a proxy or not (the proxy settings will be saved in .gradle/gradle.properties file under user's home folder)
Finish the installation.
Once it is finished the following will be installed.
DeveloperStudio application 
Blade CLI (installed into your system path if chosen so in step 5)
Liferay Workspace initialized directory (under $install_dir/liferay-workspace if chosen so in step 5)
Install in command line
Download Developer Studio.
Run the installer in command line in unattended mode.
Users can try –help for more details.
Example command:
${INSTALLER_FILE} --mode unattended --java_executable ${JAVA_EXECUTE_FILE} --productkey dxp --clitools 0 --installDir ${INSTALL_DIRECTORY}
Upgrade
Liferay Developer Studio 3.9.x is only supported with Eclipse 4.12 or greater on macOS Big Sur. This means that macOS Big Sur users can only upgrade from Liferay Developer Studio 3.9.1, 3.9.2, 3.9.3, 3.9.4, 3.9.5, and 3.9.6 on macOS Big Sur. Other users can upgrade from Liferay Developer Studio 3.5.0, 3.6.x, 3.7.x, 3.8.x and 3.9.x.
