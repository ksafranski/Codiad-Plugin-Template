# Codiad Plugin Template

This is a base for building plugins for Codiad IDE. There are 3 main components:

* `init.js` which initializes your plugin into the system
* `plugin.json` which is what Codiad uses to identify your plugin
* `README.md` which should contain information for the end-user

You can add CSS files, images, other libraries, etc. as needed for the plugin to operate successfully.

Since you have access to the `global.codiad` object you can also utilize other components in the system to modify the 
editor, work with projects, run searches, etc.