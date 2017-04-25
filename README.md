# SAML Metadata Aggregate Extractor

Run XSL transformation on SAML XML metadata to extract the metadata for an entity id.

## Windows

```bash
msxsl.exe aggregate.xml extract_entity.xsl -o metadata.xml entityID="entity-id"
```

## Linux

```bash
xsltproc --stringparam entityID entity-id extract_entity.xsl metadata.xml
```