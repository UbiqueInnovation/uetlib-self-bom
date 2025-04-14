# Uetlib Self BOM

Bill of Materials maven POM for all uetlib modules.

This project specifies the version of all `uetlib-*` modules. For third-party dependencies used by
uetlib, see [uetlib-bom](https://github.com/UbiqueInnovation/uetlib-bom).

## Using

### Add as dependency management

You can use this artifact as `dependencyManagement` for your maven project.
You can use it as following:

```xml

<dependencyManagement>
    <dependencies>
        <dependency>
            <groupId>ch.ubique</groupId>
            <artifactId>uetlib-self-bom</artifactId>
            <version>...</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```

## Changelog

See [CHANGELOG.md](CHANGELOG.md)
