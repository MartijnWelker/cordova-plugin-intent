# cordova-plugin-intent (fork)

This is a fork of `com-darryncampbell-cordova-plugin-intent` by [Moodle HQ](https://moodle.com/). If you are looking for the documentation, you can read the original at [darryncampbell/darryncampbell-cordova-plugin-intent](https://github.com/darryncampbell/darryncampbell-cordova-plugin-intent).

## Modifications from the original

We created this fork because we needed to include the following modifications in [our mobile application](https://github.com/moodlehq/moodleapp):

| PR | Description |
| -- | ----------- |
| - | Remove REQUEST_INSTALL_PACKAGES permission |
| - | Fix plugin.xml declarations |

You can see all the changes here: [ce81802...moodlemobile:v2.2.0-moodle.3](https://github.com/darryncampbell/darryncampbell-cordova-plugin-intent/compare/ce81802fcbd49cf33882ebdc65ce631b2c56df05...moodlemobile:v2.2.0-moodle.3)

## Installation

You can install this package using the [original installation instructions](https://github.com/darryncampbell/darryncampbell-cordova-plugin-intent#installation), but installing this package instead:

```sh
cordova plugin add @moodlehq/cordova-plugin-intent@2.2.0-moodle.3
```
