# JDK_MAVEN_EVOSUITE
## CONFIGURATIONS PROCESS

  #### JDK setup
1. [Install JDK 1.8.0_281](https://www.oracle.com/java/technologies/javase/8u281-relnotes.html)
   
    1. Go to Environment Variables
        1. User variables
           
              1. PATH double click
              1. New  
              1. choose the JDK directory including the bin folder
              1. e.g. C:\Program Files\Java\jdk1.8.0_281\bin
              ##### You must apply the JDK setup steps on the **System variables** as well. Keep it as the User variables format. Avoid JAVA_HOME or some other ways to setup the JDK.
              ##### Confirm with java -version in a new shell. The result should look similar to
                       
                          java version "1.8.0_281"
                          Java(TM) SE Runtime Environment (build 1.8.0_281-b09)
                          Java HotSpot(TM) 64-Bit Server VM (build 25.281-b09, mixed mode)
              ##### It should work for the  Administrator and the current user.
             
1. MAVEN setup
      1. Downloading Apache Maven](https://maven.apache.org/docs/3.6.3/release-notes.html)
            1. Binary zip archive apache-maven-3.x.x-bin.zip 
      1. unzip apache-maven-3.x.x-bin.zip
      1. Go to Environment Variables
            1. go to User variables
            1. PATH double click
            1. New  
                 1. choose Maven directory including the bin folder
                 1. e.g. C:\Program Files\MavenJar\apache-maven-3.6.3\bin
                    
            ##### You must apply the same setup steps on the **System variables** as well. Keep it as the User variables format. Avoid M2_HOME or some other ways to setup the JDK.
           ##### Confirm with mvn -version in a new shell. The result should look similar to

                Apache Maven 3.6.3 (cecedd343002696d0abb50b32b541b8a6ba2883f)
                Maven home: C:\Program Files\MavenJar\apache-maven-3.6.3\bin\..
                Java version: 1.8.0_281, vendor: Oracle Corporation, runtime: 
                C:\Program Files\Java\jdk1.8.0_281\jre
                Default locale: en_US, platform encoding: Cp1252
                OS name: "windows 10", version: "10.0", arch: "amd64", family: "windows"

1. [Go Degree Project Repository](#)

1. [EvoSuite Repository ](https://github.com/rqkohistani/EvoSuite)      
