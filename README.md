Command to create maven "war" file to deploy webapp "mvn archetype:generate -DgroupId=com.mycompany.app -DartifactId=maven-web-application -DarchetypeArtifactId=maven-archetype-webapp -DarchetypeVersion=1.4"

Defult directory structure for maven "archetype = maven-archetype-webapp" to create "WAR" file to deploy.

Maven-web-application/
├── pom.xml
└── src
    └── main
        └── webapp
            ├── WEB-INF
            │   └── web.xml
            └── index.jsp
