# BCD-UI

BCD-UI is a modern full-stack framework for building enterprise applications with web technologies.
<p/>
For more information, please have a look at 

- GitHub page https://github.com/businesscode/BCD-UI
- Documentation https://businesscode.github.io/BCD-UI-Docu
- Tutorial https://businesscode.github.io/BCD-UI-Docu/tutorial/index.html

### Using with gradle

build.gradle:
```groovy
apply plugin: 'war'

// Let this point to the root of your web application within your project
webAppDirName = "WebContent"

dependencies {
  repositories {
    mavenCentral()
    maven {
      url "https://github.com/businesscode/maven-repo/raw/master"
    }
  }
  implementation 'de.businesscode.bcdui:bcd-ui-core:5.5.0-SNAPSHOT'
  implementation 'de.businesscode.bcdui:bcd-ui-theme-bcd:5.5.-SNAPSHOT'

  // Adding Postgres JDBC, use the appropriate driver for your database 
  implementation 'org.postgresql:postgresql:42.1.4'

}
```

When using jsp, please also add
```groovy
implementation 'de.businesscode.bcdui:bcd-ui-jsptaglib:_replace_version_-SNAPSHOT'
```

### Using with maven
````xml
<project>
  <dependencies>
    <dependency>
      <groupId>de.businesscode.bcdui</groupId>
      <artifactId>bcd-ui-core</artifactId>
      <version>_replace_version_</version>
    </dependency>
    <dependency>
      <groupId>de.businesscode.bcdui</groupId>
      <artifactId>bcd-ui-theme-bcd</artifactId>
      <version>_replace_version_</version>
    </dependency>
  </dependencies>
</project>
````

BCD-UI is open-source licensed under Apache-2.0, powered by BusinessCode GmbH, Germany

<small>_replace_version_ published at _replace_date_</small>
