# oracledb-pipeline
GoCD example configuration in YAML

Install [GoCD YAML configuration plugin](https://github.com/tomzo/gocd-yaml-config-plugin) and add this to your XML config:
```xml
<config-repos>
  <config-repo pluginId="yaml.config.plugin" id="oracledb-pipeline">
    <git url="https://github.com/rdwinter2/oracledb-pipeline.git" />
  </config-repo>
</config-repos>
```
