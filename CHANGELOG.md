# Community Hass.io Add-ons: AppDaemon

All notable changes to this add-on will be documented in this file.

The format is based on [Keep a Changelog][keep-a-changelog]
and this project adheres to [Semantic Versioning][semantic-versioning].

## Unreleased

No unreleased changes yet.

## [v0.4.0] (2018-01-07)

[Full Changelog][v0.3.0-v0.4.0]

### Added

- Adds support for installing custom system and Python packages

### Changed

- Pass local CircleCI Docker socket into the build container
- Use image tagged as test as a cache resource
- Prevents possible future Docker login issue
- Upgrades add-on base image to v1.3.1
- Updated maintenance year, it is 2018

### Removed

- Removes Microbadger notification hooks

## [v0.3.0] (2017-12-03)

[Full Changelog][v0.2.2-v0.3.0]

### Changed

- Upgrades add-on base image to v1.2.0
- Improves S6 service script
- Updates add-on URLs to new community forum URL
- Moves copy of rootfs at a later stage

## [v0.2.2] (2017-11-14)

[Full Changelog][v0.2.1-v0.2.2]

### Changed

- Updated AppDaemon to v2.1.12

### Removed

- Removes `repository.json` to prevent user to install wrong repo
- Removes Gratipay from README, since it is EOL

## [v0.2.1] (2017-11-01)

[Full Changelog][v0.2.0-v0.2.1]

### Fixed

- Not possible to save `commtype` #4

## [v0.2.0] (2017-10-31)

[Full Changelog][v0.1.0-v0.2.0]

### Added

- Added `webui` link to add-on configuration #2
- Added commtype switch #1

## [v0.1.0] (2017-10-29)

### Added

- Initial release

[keep-a-changelog]: http://keepachangelog.com/en/1.0.0/
[semantic-versioning]: http://semver.org/spec/v2.0.0.html
[v0.1.0-v0.2.0]: https://github.com/hassio-addons/addon-appdaemon/compare/v0.1.0...v0.2.0
[v0.1.0]: https://github.com/hassio-addons/addon-appdaemon/tree/v0.1.0
[v0.2.0-v0.2.1]: https://github.com/hassio-addons/addon-appdaemon/compare/v0.2.0...v0.2.1
[v0.2.0]: https://github.com/hassio-addons/addon-appdaemon/tree/v0.2.0
[v0.2.1-v0.2.2]: https://github.com/hassio-addons/addon-appdaemon/compare/v0.2.1...v0.2.2
[v0.2.1]: https://github.com/hassio-addons/addon-appdaemon/tree/v0.2.1
[v0.2.2-v0.3.0]: https://github.com/hassio-addons/addon-appdaemon/compare/v0.2.2...v0.3.0
[v0.2.2]: https://github.com/hassio-addons/addon-appdaemon/tree/v0.2.2
[v0.3.0-v0.4.0]: https://github.com/hassio-addons/addon-appdaemon/compare/v0.3.0...v0.4.0
[v0.3.0]: https://github.com/hassio-addons/addon-appdaemon/tree/v0.3.0
[v0.4.0]: https://github.com/hassio-addons/addon-appdaemon/tree/v0.4.0
