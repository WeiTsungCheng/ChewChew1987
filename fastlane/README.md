fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios register_app

```sh
[bundle exec] fastlane ios register_app
```



### ios get_dev_cert_and_sign

```sh
[bundle exec] fastlane ios get_dev_cert_and_sign
```



### ios sync_device_info

```sh
[bundle exec] fastlane ios sync_device_info
```

Update iOS UDID's on the Developer Portal

### ios sync_signing_assets

```sh
[bundle exec] fastlane ios sync_signing_assets
```

Sync team Code-Signing assets

### ios build_appstore

```sh
[bundle exec] fastlane ios build_appstore
```

Build for App Store submission

### ios build_adhoc

```sh
[bundle exec] fastlane ios build_adhoc
```

Build for Ad Hoc submission

### ios distribute_to_appstore

```sh
[bundle exec] fastlane ios distribute_to_appstore
```



### ios distribute_to_installer

```sh
[bundle exec] fastlane ios distribute_to_installer
```



### ios release

```sh
[bundle exec] fastlane ios release
```



----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
