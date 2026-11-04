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
            <groupId>ch.uetlib</groupId>
            <artifactId>uetlib-self-bom</artifactId>
            <version>6.0.0</version>
            <type>pom</type>
            <scope>import</scope>
        </dependency>
    </dependencies>
</dependencyManagement>
```

## Changelog

See [CHANGELOG.md](CHANGELOG.md)

## License

Except where otherwise noted, original uetlib code is licensed under the [Apache License 2.0](LICENSE). Third-party files retain their original license terms; see [NOTICE](NOTICE) and any third-party notices in this repository.
