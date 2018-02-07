## Summary

This plugin auto-generates an identifier for Digital Objects created in staff mode (frontend).

---

## Activate the plugin
- Install the plugin:
  - Clone this repository into the _plugins/autogenerate-doid_ directory; or
  - Unzip/untar the release zip/tar into the _plugins/autogenerate-doid_ directory.

- Enable the plugin:
  - In config/config.rb, add the plugin name to the "AppConfig[:plugins]" list, e.g.:

    AppConfig[:plugins] = ['autogenerate-doid']

- Restart ArchivesSpace
