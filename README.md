# BCD-UI

BCD-UI is a modern full-stack framework for building enterprise applications with web technologies.
<p/>
For more information please have a look at 

- GitHub page https://github.com/businesscode/BCD-UI
- Documentation https://businesscode.github.io/BCD-UI-Docu

### Using with gradle 

```groovy
dependencies {
  repositories {
    mavenCentral()
    maven {
      url "https://github.com/businesscode/maven-repo/raw/master"
    }
    implementation 'de.businesscode.bcdui:bcd-ui-core:5.5.0-SNAPSHOT'
    implementation 'de.businesscode.bcdui:bcd-ui-theme-bcd:5.5.0-SNAPSHOT'
  }
}
```

When using jsp, please also add
```gradle
implementation 'de.businesscode.bcdui:bcd-ui-jsptaglib:5.5.0-SNAPSHOT'
```

### Using with maven
````xml
<project>
  <dependencies>
    <dependency>
      <groupId>de.businesscode.bcdui</groupId>
      <artifactId>bcd-ui-core</artifactId>
      <version>5.5.0</version>
    </dependency>
    <dependency>
      <groupId>de.businesscode.bcdui</groupId>
      <artifactId>bcd-ui-theme-bcd</artifactId>
      <version>5.5.0</version>
    </dependency>
  </dependencies>
</project>
````
<small>5.5.0 published at 2021-06-15 12:36:26</small>
