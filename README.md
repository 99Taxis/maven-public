Maven Public
============

This repository contains some public Maven artifacts
which are not present in the central Maven repository
or which are not published as Maven artifacts at all.

To use it, add the repository to your pom.xml file:


    <repository>
      <id>99taxis-github-maven-repo</id>
      <url>https://raw.github.com/99taxis/maven-public/master/releases</url>
      <snapshots>
        <enabled>false</enabled>
      </snapshots>
    </repository>

If your really need it, add the snapshots repository


    <repository>
      <id>99taxis-snapshot-github-maven-repo</id>
      <url>https://raw.github.com/99taxis/maven-public/master/snapshots</url>
      <snapshots>
        <enabled>true</enabled>
        <!-- never, daily, interval:X (where X is in minutes) or always -->
        <updatePolicy>always</updatePolicy>
      </snapshots>
      <releases>
        <enabled>false</enabled>
      </releases>
    </repository>

## Most up-to-date artifacts

### com.taxis99:zendesk-java-api:1.0.5


    <dependency>
      <groupId>com.taxis99</groupId>
      <artifactId>zendesk-java-api</artifactId>
      <version>1.0.5</version>
    </dependency>

### com.taxis99:mailchimp-java-api:1.0-SNAPSHOT


    <dependency>
      <groupId>com.taxis99</groupId>
      <artifactId>mailchimp-java-api</artifactId>
      <version>1.0-SNAPSHOT</version>
    </dependency>

### fi.foyt:foursquare-api:1.0.3-SNAPSHOT

Built upon [foursquare-api-java 20140131 branch](https://github.com/clinejj/foursquare-api-java/tree/20140131), commit [#f3f85f6b](https://github.com/clinejj/foursquare-api-java/commit/f3f85f6b66ffccb5eb8a50daa0aa016bffc6155d)
    
    <dependency>
      <groupId>fi.foyt</groupId>
      <artifactId>foursquare-api</artifactId>
      <version>1.0.3-SNAPSHOT</version>
    </dependency>
