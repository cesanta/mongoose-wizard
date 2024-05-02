# Mongoose Wizard

[Mongoose Wizard](https://mongoose.ws/wizard/) is a no-code visual tool for creating connected applications on embedded devices.

<details>
<summary>How to report errors</summary>
  
Just add an issue to this repository. In the issue, explain how to reproduce the issue. Things that can help:
1. If you work with a specific UI setup, "export" is and attach the exported configuration to the issue. It will make it easier to reproduce.
2. If the UI stops responding, this is probably due to the JavaScript bug. Collect more information as described below:
3. Open developer tools, and click on the console tab, like this. Copy-paste the backtrace as shown and attach it to the report: <br/> <img width="570" alt="image" src="https://github.com/cesanta/mongoose-wizard/assets/601816/d2812c58-deb9-4bb7-bc50-a5ab73a355af">
4. Then click on the top-most entry of the backtrace, and copy-paste the snippet, too: <br/> <img width="873" alt="image" src="https://github.com/cesanta/mongoose-wizard/assets/601816/0a74b7b1-c7a0-4d9a-8d48-75191fbfe9e7">
</details>

## Changelog

- 2024-05-02 Replaced 'enum' with 'list' - dropdowns handling must be updated! Done panel loading UI. Updated glue_mqtt_publish: added topic arg
- 2024-04-24 Added 'file' and 'ota' variables and associated 'upload' widget. Simplified text API signature, added `glue_printf()`
- 2024-04-23 Added 'action' variable and associated 'button' widget. Fixed some issues
- 2024-04-20 More precise control over widget placement. Added gauge and progress widgets
- 2024-04-19 Issue 1 10/14 fixed
- 2024-04-18 Added this repo, added outstanding issues, fixed 3 of them
