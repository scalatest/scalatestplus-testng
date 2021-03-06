# ScalaTest + TestNG
ScalaTest + TestNG provides integration support between ScalaTest and TestNG.

**Usage**

To use it for ScalaTest 3.2.9 and TestNG 6.7.x: 

SBT: 

```
libraryDependencies += "org.scalatestplus" %% "testng-6-7" % "3.2.9.0" % "test"
```

Maven: 

```
<dependency>
  <groupId>org.scalatestplus</groupId>
  <artifactId>testng-6-7_2.13</artifactId>
  <version>3.2.9.0</version>
  <scope>test</scope>
</dependency>
```

**Publishing**

Please use the following commands to publish to Sonatype: 

```
$ sbt +publishSigned
```
