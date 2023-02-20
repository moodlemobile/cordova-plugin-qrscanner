# cordova-plugin-qrscanner (fork)

This is a fork of `cordova-plugin-qrscanner` by [Moodle HQ](https://moodle.com/). If you are looking for the documentation, you can read the original at [bitpay/cordova-plugin-qrscanner](https://github.com/bitpay/cordova-plugin-qrscanner).

## Modifications from the original

We created this fork because we needed to include the following modifications in [our mobile application](https://github.com/moodlehq/moodleapp):

| PR | Description |
| -- | ----------- |
| [#266](https://github.com/bitpay/cordova-plugin-qrscanner/pull/266) | fix openSettingsURLString deprecated function |
| [#382](https://github.com/bitpay/cordova-plugin-qrscanner/pull/382) | fix: Remove style attribute from body for prevent unexpected background |
| - | fix: Replace compile() with implementation() |

It also includes some commits that are in master and haven't been released, and the distribution assets have been added to the repository.

You can see all the changes here: [111fa6c...moodlemobile:v3.0.1-moodle.5](https://github.com/bitpay/cordova-plugin-qrscanner/compare/111fa6c272da6c708b65528baea2316542e421fa...moodlemobile:v3.0.1-moodle.5)

## Installation

You can install this package using the [original installation instructions](https://github.com/bitpay/cordova-plugin-qrscanner#get-started), but installing this package instead:

```sh
cordova plugin add @moodlehq/cordova-plugin-qrscanner@3.0.1-moodle.5
```
