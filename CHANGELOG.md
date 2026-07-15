# [1.3.0](https://github.com/databk/rustdesk-console-web/compare/1.2.2...1.3.0) (2026-07-15)


### Features

* add custom client generation via Nexus API ([#180](https://github.com/databk/rustdesk-console-web/issues/180)) ([2c5b2a5](https://github.com/databk/rustdesk-console-web/commit/2c5b2a5c7dd16e6ee0d38d35e3d75d782d47c5b4))
* add Portuguese (Brazil) localization support ([#175](https://github.com/databk/rustdesk-console-web/issues/175)) ([811a9fe](https://github.com/databk/rustdesk-console-web/commit/811a9fed8d157d4a96100002206935a89284da2e))
* add update check support for POST /api/update-check ([#169](https://github.com/databk/rustdesk-console-web/issues/169)) ([04a6527](https://github.com/databk/rustdesk-console-web/commit/04a652757144b0e87d715b5199ecdee29075039e))
* make SMTP user and pass fields optional to support non-auth servers ([#181](https://github.com/databk/rustdesk-console-web/issues/181)) ([bc47f52](https://github.com/databk/rustdesk-console-web/commit/bc47f527204e3cd05206b7c1502168b9d8e6ea7a))



## [1.2.2](https://github.com/databk/rustdesk-console-web/compare/1.2.1...1.2.2) (2026-06-20)


### Bug Fixes

* resolve invisible 2FA verification inputs and buttons on login page ([#162](https://github.com/databk/rustdesk-console-web/issues/162)) ([f814549](https://github.com/databk/rustdesk-console-web/commit/f814549906dd86626e26795419554c345c81c903))
* use tfa_type field to determine 2FA verification type on login ([#163](https://github.com/databk/rustdesk-console-web/issues/163)) ([3ac025d](https://github.com/databk/rustdesk-console-web/commit/3ac025df0d7f2ced30991a76ad08b7707c1815df))


### Reverts

* Revert "chore(deps-dev): bump @biomejs/biome from 2.4.16 to 2.5.0 (#159)" (#161) ([208fe7f](https://github.com/databk/rustdesk-console-web/commit/208fe7fbf5789a244909dcd1c4df68c33dd35887)), closes [#159](https://github.com/databk/rustdesk-console-web/issues/159) [#161](https://github.com/databk/rustdesk-console-web/issues/161)



## [1.2.1](https://github.com/databk/rustdesk-console-web/compare/1.2.0...1.2.1) (2026-06-15)


### Bug Fixes

* align react and react-dom versions to 19.2.7 ([#160](https://github.com/databk/rustdesk-console-web/issues/160)) ([a6decec](https://github.com/databk/rustdesk-console-web/commit/a6dececa384e290cf61abf0720490b6c188eca07)), closes [#527](https://github.com/databk/rustdesk-console-web/issues/527)



# [1.2.0](https://github.com/databk/rustdesk-console-web/compare/1.1.2...1.2.0) (2026-06-14)


### Bug Fixes

* use explicit version tags for Docker images ([#155](https://github.com/databk/rustdesk-console-web/issues/155)) ([3dbc6f8](https://github.com/databk/rustdesk-console-web/commit/3dbc6f8468d03189998fb39cb26d56eba9defcae))


### Features

* add LDAP configuration settings page ([#153](https://github.com/databk/rustdesk-console-web/issues/153)) ([9754767](https://github.com/databk/rustdesk-console-web/commit/9754767baeff06c9f2f9d23d228e0abea1c25452))
* display user avatar in header navigation bar ([#150](https://github.com/databk/rustdesk-console-web/issues/150)) ([2cdba60](https://github.com/databk/rustdesk-console-web/commit/2cdba6051202f92739c8bcd3dfe5d5d72add9273))
* implement alarm audit query and extract shared name@ip logic ([#151](https://github.com/databk/rustdesk-console-web/issues/151)) ([669aa13](https://github.com/databk/rustdesk-console-web/commit/669aa137e0bed2b83cc00b742f59e846c0a92465))
* update release workflow to auto-generate version ([#154](https://github.com/databk/rustdesk-console-web/issues/154)) ([cd298ad](https://github.com/databk/rustdesk-console-web/commit/cd298adce8eaf7dc41a66e855c163c8b1fa2a771))



## [1.1.2](https://github.com/databk/rustdesk-console-web/compare/1.1.1...1.1.2) (2026-06-07)


### Bug Fixes

* hide SettingDrawer in production environment ([#143](https://github.com/databk/rustdesk-console-web/issues/143)) ([7b00e05](https://github.com/databk/rustdesk-console-web/commit/7b00e05fe591741f137ae4f7b0f145bb86356f5f))



