eXo Platform Addon maven archetype
=======

This maven archetype generates the folder and files structure ready to develop a new addon for eXo Platform.

Command line to launch is :

    mvn archetype:generate -DarchetypeGroupId=org.exoplatform.addons -DarchetypeArtifactId=exo-addon-archetype -DarchetypeVersion=1.0-SNAPSHOT
    
This will ask some parameters :
* addon groupId
* addon artifactId
* addon version
* addon package name (this property is not used)

The addon structure will be

* packaging
    * src
        * main
            * assemblies
                * assembly-addon.xml
     * pom.xml
* service
    * pom.xml
* war
    * src
        * main 
            * webapp
                * META-INF
                    * exo-conf
                        * configuration.xml
                * WEB-INF
                    * web.xml
    * pom.xml
* pom.xml
* README.md
 
        

