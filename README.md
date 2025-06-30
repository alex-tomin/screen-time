# Screen Time

IoT project to track kid's screen time

# How to Contribute

## To Release a Version

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

   1. If build is successful a release will be created automatically with necessary assets - validate manifest and firmware files are attached
   2. Git tags are automatically added (extracted from project version above)
   3. Review Release description.
   4. Mark Release as `latest` if you want the updated to automatically pick it up.

# License

Free for personal and non-profit use. See [License Agreement](LICENSE) for more details.
