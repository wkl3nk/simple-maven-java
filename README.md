# simple-maven-java

Simple maven project that allows to deploy packages on 
maven.pkg.github.com

```mvn clean package```

```mvn deploy```

The ```distributionManagement``` section in the ```pom.xml``` file references the maven repository on github
with id ```wkl3nk-github-packages```. 

The ```$HOME/.m2/settings.xml``` file contains the credentials for this maven repository.

The ```password``` is a personal access token (PAT) that is created in the github account settings.
This PAT requires the ```write:packages``` scope and ```repo``` scopes.

Explicitly added a copyleft license to the project.

(C) 2024 Wolfgang Klenk

