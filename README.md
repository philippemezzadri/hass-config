### Package config files for Home Assistant

Copy YAML files in `/config/packages/`

Add the following in `configuration.yaml`:

```yaml
homeassistant:
  packages: !include_dir_named packages
```

for more info, see [Packages](<https://www.home-assistant.io/docs/configuration/packages/>) in Home Assistant documentation.
