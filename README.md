# Screen Time

IoT project to track kid's screen time

# How to Contribute

## To Release a Version

1) update version in file;   2) Push  3) Mark release as latest, update text.  (auto updater only checks for latest)

1. Update version in `screen-time.yaml` , `esphome -> project -> version`section. e.g.

   ```diff
   esphome:
     project:
       name: tomin.screen-time
   +   version: "1.0.5"
   ```
2. Add details to `release-notes.md` file.
3. Push your changes, validate build on GitHub Actions.
4. Update Release

   1. If build is successful a release wil b ecreated automtically with necessary assets - validate manifest and firmware files are attached
   2. Review Release description.
   3. Mark Release as `latest` if you want the updated to automatically pick it up.

# License

Free for personal and non-profit use. See [License Agreement](LICENSE) for more details.
