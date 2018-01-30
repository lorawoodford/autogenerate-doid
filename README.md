## Summary

This plugin auto-generates an identifier for Digital Objects created in staff mode (frontend).

This version of the plugin is known to work in ArchivesSpace version 1.5.4.

---

## Activate the plugin
- Install the plugin:
  - Clone this repository into the _plugins/jhu-autogenerate-doid directory_; or
  - Unzip/untar the release zip/tar into the _plugins/jhu-autogenerate-doid_ directory.

- Enable the plugin:
  - In config/config.rb, add the plugin name to the "AppConfig[:plugins]" list, e.g.:

    AppConfig[:plugins] = ['jhu-autogenerate-doid']

- Restart ArchivesSpace
