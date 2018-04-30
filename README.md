# Struts Example

Repo for Spring Bootification of Struts lab

## Build the app with maven

```
$ mvn clean package
```

## Deploy the war to PCF

```
$ cf push struts-example -p target/struts.war
```
