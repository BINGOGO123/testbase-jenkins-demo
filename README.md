# testbase-package-jenkins

This is a single step sample for Jenkins azure-testbase-plugin. `java-demo.zip` is a pre-packaged file contains installer and test scripts. `Jenkinsfile` has only one step, and that's to onboard this package with azure-testbase-plugin.

`TestBase.json` and `TestBase-simple.json` are the configuration file for azure-testbase-plugin. `TestBase.json` contains complete parameters this plugin supported, and `TestBase-simple.json` only contains mandatory parameters for this plugin. You can write configuration in either of the two in advance. And if you don't want to use this kind of extra configuration file to configure azure-testbase-plugin, you can also congifure these options during the creation of freestyle job or generate pipeline statement from syntax generator.