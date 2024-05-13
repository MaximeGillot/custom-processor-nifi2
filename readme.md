
# Initialisation  

à faire après création du processor :

dans le nom du package, supprimer le true
penser aussi à modifier le true dans le meta-inf

changer la dependency dans le pom du nifi-true-nar
passer de la 1.0.0-SNAPSHOT de nifi-standard-services-api-nar à la 2.0.0-M2 :

```xml
    <groupId>org.apache.nifi</groupId>
    <artifactId>nifi-standard-services-api-nar</artifactId>
    <version>2.0.0-M2</version>
    <type>nar</type>
```