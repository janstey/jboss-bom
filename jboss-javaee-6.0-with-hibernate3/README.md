JBoss Java EE 6 with Hibernate 3
================================

This BOM builds on the Java EE full profile BOM, adding Hibernate Community projects including Hibernate 3 ORM, Hibernate
Entity Manager (JPA 1.0) and Hibernate Validator.

Usage
-----

To use the BOM, import into your dependency management:

    <dependencyManagement>
        <dependencies>
            <dependency>
              <groupId>org.jboss.bom.eap</groupId>
              <artifactId>jboss-javaee-6.0-with-hibernate3</artifactId>
              <version6.1.0-redhat-SNAPSHOT</version>
              <type>pom</type>
              <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>

