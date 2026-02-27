# MRE for an issue at Quarkus.

The project was created via the following command.

```bash
quarkus create app org.acme:getting-started \
    --extension='rest'
```

SBOMs were created via `mvn quarkus:dependency-sbom`.

A copy of those are located in the file [getting-started-1.0.0-SNAPSHOT-dependency-cyclonedx.json](getting-started-1.0.0-SNAPSHOT-dependency-cyclonedx.json).
