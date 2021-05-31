# BCD-UI <span style="font-size: 30%">5.5.0 published at 2021-05-31 18:37:17</span>

BCD-UI is a full-stack framework for building enterprise applications with web technologies.
<p/>
For more information have a look at 

- Documentation https://businesscode.github.io/BCD-UI-Docu
- Project page https://github.com/businesscode/BCD-UI

### Usage with gradle 

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

### Usage with maven
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
