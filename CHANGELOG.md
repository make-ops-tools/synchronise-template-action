# Changelog

## [1.2.0](https://github.com/make-ops-tools/synchronise-template-action/compare/v1.1.3...v1.2.0) (2023-09-17)


### Features

* :rocket: ([#328](https://github.com/make-ops-tools/synchronise-template-action/issues/328) [#316](https://github.com/make-ops-tools/synchronise-template-action/issues/316)) add params for git user.name, user.email a… ([#330](https://github.com/make-ops-tools/synchronise-template-action/issues/330)) ([6038fdf](https://github.com/make-ops-tools/synchronise-template-action/commit/6038fdfeb863b03c9c451ae039347fbeb1b7a3e4))
* ability to add reviewers for pull requests ([#362](https://github.com/make-ops-tools/synchronise-template-action/issues/362)) ([964b161](https://github.com/make-ops-tools/synchronise-template-action/commit/964b16174a24d517420640c0e81466c93491c147))
* **action:** add parameter for gh action configuration ([#129](https://github.com/make-ops-tools/synchronise-template-action/issues/129)) :rocket: ([55484dc](https://github.com/make-ops-tools/synchronise-template-action/commit/55484dc36dd0cc1313d4d946194463955a2f4be1))
* add configurable PR title and branch prefix ([2d80a8a](https://github.com/make-ops-tools/synchronise-template-action/commit/2d80a8a1a9f77ac171908181acc909f54554ac6a))
* config files inside .GitHub folder ([#252](https://github.com/make-ops-tools/synchronise-template-action/issues/252)) ([8aa35f1](https://github.com/make-ops-tools/synchronise-template-action/commit/8aa35f14a22f32995bb4822c3822dfcd5c03b082))
* **docker:** push image to registries ([7e8787a](https://github.com/make-ops-tools/synchronise-template-action/commit/7e8787a6f4b693bde965ec9a1a62f62cb430c980))
* **docker:** push image to registries ([93d70a3](https://github.com/make-ops-tools/synchronise-template-action/commit/93d70a3b9b2c4cdfc11e910e6c3a92b01b294f79))
* **docker:** push image to registries :rocket: ([5bab502](https://github.com/make-ops-tools/synchronise-template-action/commit/5bab50211ab29a634a5ab96bffb3acc766fbceb6))
* **docker:** push image to registries :rocket: ([8310801](https://github.com/make-ops-tools/synchronise-template-action/commit/83108019523c1167e23d10086ab2d59835be0fe1))
* **docker:** push image to registries :rocket: ([a54c0ff](https://github.com/make-ops-tools/synchronise-template-action/commit/a54c0ffc5048ff186e3ee51cc2c97fbb98cb5615))
* **docker:** push image to registries :rocket: ([f88b658](https://github.com/make-ops-tools/synchronise-template-action/commit/f88b6587706e90e8dbbbe937997db9ad70f34114))
* **docker:** push image to registries :rocket: ([5f162c8](https://github.com/make-ops-tools/synchronise-template-action/commit/5f162c8c9e194d90828379c5b68a90e22227862f))
* **gh-auth:** add gh auth login and credential helper ([#239](https://github.com/make-ops-tools/synchronise-template-action/issues/239)) ([7a33121](https://github.com/make-ops-tools/synchronise-template-action/commit/7a33121add81c181094cdb290a4cc9bf654c918d))
* **hostname:** add hostname :rocket: ([cb89c88](https://github.com/make-ops-tools/synchronise-template-action/commit/cb89c8896a58539de04d1ba46100e69fc3e08145))
* make commit msg configurable ([#237](https://github.com/make-ops-tools/synchronise-template-action/issues/237)) ([764e725](https://github.com/make-ops-tools/synchronise-template-action/commit/764e7250dac337e260c8f28aba63da9da2016b45))
* **self:** add self as action template :rocket: ([80f10a5](https://github.com/make-ops-tools/synchronise-template-action/commit/80f10a55914de3a35749a783c8d8ef4bb567c4c8))


### Bug Fixes

* :bug: ([#375](https://github.com/make-ops-tools/synchronise-template-action/issues/375)) fix edge case with .templatesyncignore ([#378](https://github.com/make-ops-tools/synchronise-template-action/issues/378)) ([1eede30](https://github.com/make-ops-tools/synchronise-template-action/commit/1eede30772357d6984d1757753a672da4119d356))
* :bug: ([#380](https://github.com/make-ops-tools/synchronise-template-action/issues/380)) small fix related to remote file mode changes ([#383](https://github.com/make-ops-tools/synchronise-template-action/issues/383)) ([ff25f8c](https://github.com/make-ops-tools/synchronise-template-action/commit/ff25f8cbcd237716eeff23dc5616632c7663e99f))
* :bug: fix condition ([5563bf1](https://github.com/make-ops-tools/synchronise-template-action/commit/5563bf1b748efd19b411f4a8f0ac9dc12693dd41))
* :bug: run of workflows in forked repos ([#312](https://github.com/make-ops-tools/synchronise-template-action/issues/312)) ([#313](https://github.com/make-ops-tools/synchronise-template-action/issues/313)) ([53177e2](https://github.com/make-ops-tools/synchronise-template-action/commit/53177e27db816fcb36efceaf0e1e05956d58cc30))
* (lint) fix md lint issue :bug: ([a95853f](https://github.com/make-ops-tools/synchronise-template-action/commit/a95853fb974d5a41e6268437abb8c549b124a1ba))
* checkout action using a github pat ([#358](https://github.com/make-ops-tools/synchronise-template-action/issues/358)) ([9e4223d](https://github.com/make-ops-tools/synchronise-template-action/commit/9e4223d7a38b5c32d29100ad5b59fe5154f9ab2f))
* **config:** fix pr_labels -&gt; now complete optional ([#207](https://github.com/make-ops-tools/synchronise-template-action/issues/207)) :rocket: ([f9de1ad](https://github.com/make-ops-tools/synchronise-template-action/commit/f9de1ad1421d68ac4ec10cd6b9a8963cfa6e81b5))
* **cve:** ([#168](https://github.com/make-ops-tools/synchronise-template-action/issues/168)) fix bug related to CVE-2022-24765 :lock: ([e231a7b](https://github.com/make-ops-tools/synchronise-template-action/commit/e231a7b1e54f1fc1ad9244bb83b6983fd76ab919))
* **cve:** fix bug related to CVE-2022-24765 :lock: ([6a6128f](https://github.com/make-ops-tools/synchronise-template-action/commit/6a6128fd209f833bd6e6c28944d152668a701ac8))
* **divergent_branches:** ([#142](https://github.com/make-ops-tools/synchronise-template-action/issues/142)) fix issue with divergent branches :bug: ([40d1558](https://github.com/make-ops-tools/synchronise-template-action/commit/40d1558936bc53edf8e689a20e46e866b135b9ec))
* quote PR title ([bcf13f1](https://github.com/make-ops-tools/synchronise-template-action/commit/bcf13f16e35f689c001e63d94303189dfabb78a6))
* **sync-template:** fix issue with .templatesyncignore conflicts ([#251](https://github.com/make-ops-tools/synchronise-template-action/issues/251)) ([dd6bb2c](https://github.com/make-ops-tools/synchronise-template-action/commit/dd6bb2c1ff98261bbd48933ba3b776b555801953))
* **sync-template:** IF order ([#269](https://github.com/make-ops-tools/synchronise-template-action/issues/269)) ([00e2f35](https://github.com/make-ops-tools/synchronise-template-action/commit/00e2f35f579355b6a06d6cc6f2778da5c9a1673e))
* **sync-template:** typo in TEMPLATE_SYNC_IGNORE_FILE_PATH variables ([#268](https://github.com/make-ops-tools/synchronise-template-action/issues/268)) ([67b630b](https://github.com/make-ops-tools/synchronise-template-action/commit/67b630b03e20241b950f85a4832d49b7cadf8c18))

## [1.1.3](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.2...v1.1.3) (2023-09-16)


### Bug Fixes

* :bug: ([#380](https://github.com/AndreasAugustin/actions-template-sync/issues/380)) small fix related to remote file mode changes ([#383](https://github.com/AndreasAugustin/actions-template-sync/issues/383)) ([ff25f8c](https://github.com/AndreasAugustin/actions-template-sync/commit/ff25f8cbcd237716eeff23dc5616632c7663e99f))

## [1.1.2](https://github.com/AndreasAugustin/actions-template-sync/compare/v1.1.1...v1.1.2) (2023-09-03)


### Bug Fixes

* :bug: ([#375](https://github.com/AndreasAugustin/actions-template-sync/issues/375)) fix edge case with .templatesyncignore ([#378](https://github.com/AndreasAugustin/actions-template-sync/issues/378)) ([1eede30](https://github.com/AndreasAugustin/actions-template-sync/commit/1eede30772357d6984d1757753a672da4119d356))
