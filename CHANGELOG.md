# [1.4.0](https://github.com/databk/rustdesk-console-web/compare/1.3.0...1.4.0) (2026-07-22)


### Features

* add columns state persistence to all ProTable instances ([#190](https://github.com/databk/rustdesk-console-web/issues/190)) ([8013358](https://github.com/databk/rustdesk-console-web/commit/8013358a0859e43812f6120ea56310aee737a549))
* add console general settings and configurable watermark ([#197](https://github.com/databk/rustdesk-console-web/issues/197)) ([56839cb](https://github.com/databk/rustdesk-console-web/commit/56839cb06e07b270b9dbe9edcfbfaa2aeebd1b50))
* add display_name field support for users ([#195](https://github.com/databk/rustdesk-console-web/issues/195)) ([440d319](https://github.com/databk/rustdesk-console-web/commit/440d31971f1274f493034ba295a3be6b1d7a54e2))
* add linux/arm64 Docker image build support ([#196](https://github.com/databk/rustdesk-console-web/issues/196)) ([16671bc](https://github.com/databk/rustdesk-console-web/commit/16671bc873ba09f9560c082fa40ac26c6ee0dc07))
* add user_group_guid field to user update ([#203](https://github.com/databk/rustdesk-console-web/issues/203)) ([0515620](https://github.com/databk/rustdesk-console-web/commit/05156206d9f9738e39bc59767f804e2499d72ae3))
* complete user-group management workflows ([#188](https://github.com/databk/rustdesk-console-web/issues/188)) ([7443ce1](https://github.com/databk/rustdesk-console-web/commit/7443ce1e875a179a38f30cd365ee93d67bc498eb))
* extend address book sharing to support individual users and everyone ([#200](https://github.com/databk/rustdesk-console-web/issues/200)) ([13a059e](https://github.com/databk/rustdesk-console-web/commit/13a059e5118d35cb1922a13e37929af0a9c44379))
* implement drag sort for OIDC providers ([#199](https://github.com/databk/rustdesk-console-web/issues/199)) ([3604d41](https://github.com/databk/rustdesk-console-web/commit/3604d41b711e0a419e19dc0f00a83c05333e9aec))
* manage custom address books from the personal page ([#189](https://github.com/databk/rustdesk-console-web/issues/189)) ([901a24c](https://github.com/databk/rustdesk-console-web/commit/901a24c7f724024b5251619136966599b7cb7918))


### Reverts

* remove site name functionality from commit 56839cb ([#202](https://github.com/databk/rustdesk-console-web/issues/202)) ([8fc55cc](https://github.com/databk/rustdesk-console-web/commit/8fc55cc8af04be0650a2e3ef1e66722f836fe796))



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



