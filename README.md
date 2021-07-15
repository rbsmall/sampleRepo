# sampleRepo
This sample repository reflects one possible way to structure your application repository.  

The initial folder, myApplicationName, should be set to reflect the name of the application the source files pertain to.  

**IMPORTANT** : The [.gitattributes] file in the root folder of the repository is required by the Rocket Git component installed in Unix Systems Services (USS) on the mainframe to correctly translate source files as they are transferred between the enterprise Git server and USS.  The [application-conf] folder under the high-level application folder is a requirement for the sample zAppBuild framework utilized by Dependency Based Build (DBB). 