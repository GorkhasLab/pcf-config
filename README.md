# pcf-config
- Modify .iml file to add following like of structure to achieve auto completion in yml file.
```xml
<?xml version="1.0" encoding="UTF-8"?>
<module ...>
  <component name="FacetManager">
    <facet type="Spring" name="Spring">
      <configuration spring_boot_spring_config_custom_files="file://$MODULE_DIR$/uaa-keycloak.yml;file://$MODULE_DIR$/demo.yml;file://$MODULE_DIR$/api-gateway-keycloak.yml" />
    </facet>
    <facet type="web" name="Web">
      <configuration>
        <webroots />
      </configuration>
    </facet>
  </component>
  ...
</module>
```