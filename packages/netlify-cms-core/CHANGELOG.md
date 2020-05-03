# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

# 2.25.0-beta.1 (2020-05-03)


### Bug Fixes

* add missing generic type to registerPreviewTemplate ([#3597](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3597)) ([36ae69c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/36ae69c96eded5f4af4a9bd63e319f64b62b0e63))
* allow unlimited alias count ([#3570](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3570)) ([bfb2e2b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/bfb2e2bc574d9b356aa14ffb3b6eb7eca285c73a))
* allow widgets to control value to be validated ([#3448](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3448)) ([ae1917c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ae1917c8181892a439d0828d98992788fb48d65c))
* cache assets using resolved path on error ([#3378](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3378)) ([f3fd43b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f3fd43b81928abaea99b50ee4223de3c0498cb71))
* call createDraftFromEntry after entry is loaded instead in Editor ([#3418](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3418)) ([2409323](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2409323dba1abe8a670d18453369fd75c6e240fb))
* change default open authoring scope, make it configurable ([#2821](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2821)) ([002cdd7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/002cdd77a856bde3672e75dde6d3a2b246e1035f))
* consider variable types when traversing collection fields ([#3347](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3347)) ([961cde4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/961cde4ea523027a1367bbdb84adbc2843a79b57))
* don't override empty public folder ([#3513](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3513)) ([a1bf86e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a1bf86e8566dfad123926339b16d9a16a4bfd77a))
* don't use getAsset for draft entries ([#3403](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3403)) ([45a1654](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/45a1654404ef7bd24dd2f04a4b3f896d1eef0b7d))
* dupe entry declaration ([029f13b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/029f13b7d9387b7567696e19538c6a6ff72136c3))
* dupe entry declaration ([97f3aca](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/97f3aca412e33cccbcd00e3e33eada9575e5c345))
* duplicate entry ([#3563](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3563)) ([1d88b15](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1d88b15de54d62d1d8d40a0391e9fc640af2ca97))
* enable merge option for yaml parser ([#3577](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3577)) ([b8eeab2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b8eeab2e35a51cb8128d2a0df23d8ecd489208cd))
* ensure draft changes ([#3306](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3306)) ([cf81f58](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cf81f587cf517b2906e261e89090de984aad3ce3))
* esm extensions ([eff4b28](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/eff4b285265e4698e7e842abc11673810409dfbc))
* ja locale labels ([#3367](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3367)) ([50837b0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/50837b0068ac8972ce16cbf5f238aa5a2c5bd6e9))
* media files when duplicating entry ([#3507](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3507)) ([9705295](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/970529570b11bbcf3fb65e91f2be09b699b20be7))
* missing widgets ([#3541](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3541)) ([6933bf6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6933bf6ee1acbbefb2cc7840a8aef6accc2d455b))
* pass prettyErrors to yaml when parsing config ([#3571](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3571)) ([0d59642](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0d59642e64e9341b3ac73ede4cfb0e4ba2980faa))
* preserve unknown fields value ([#3314](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3314)) ([908c42f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/908c42fb588ce87f4e197df65db2d238f34837f4))
* redirect to default path after login success if url has prev error ([#3599](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3599)) ([bb0a7e9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/bb0a7e96d82d950735eafce3017460caf0fd6d0c))
* sidebar icon shrinking when label wraps ([#3653](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3653)) ([a9d0699](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a9d0699a82a25d79dd99af4f1ed9643ce7bba220))
* support common backend configuration options from docs in ts types ([#3674](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3674)) ([2580251](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/25802512087854e23333837d48a284832d9d50b2))
* **backend-github:** improve workflow migration edge cases/messaging ([#3319](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3319)) ([684b79e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/684b79e43bebb63ce1e844eae5c8c0e76087687b))
* **core:** improve editor buttons for smaller screens ([#3327](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3327)) ([53365b7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/53365b73701c872948a1e65da00a655e0718e8cb))
* **core:** report config error when external media lib is missing ([#3255](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3255)) ([1d63038](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1d63038e78a6db1e7a061b5ba447f951d892595a))
* **sort:** don't clear sort data on entries request ([#3648](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3648)) ([cf57284](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cf57284f40141712e3265992bdf6966a5c81f838))
* **type-defs:**  add string type to EditorComponentData id property ([#3602](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3602)) ([1a60e6d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1a60e6d7fde3c282df23487cd1f7479b0b848873))
* **types:** instead of the inferred {}, allow any kind of props ([#3638](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3638)) ([3f72f43](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3f72f438a1e2ad1111780208af69bf172becd277))
* .d.ts definitions for core and app ([#2929](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2929)) ([7391061](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7391061b3b8b1971b994f497a6df29b7d5c3da74))
* allow absolute paths for collection media folder ([#3160](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3160)) ([a215cfb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a215cfbe3aa875fb932878039a5efbde6d97b538))
* always ensure collection exists before routing ([#2992](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2992)) ([982fd7b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/982fd7b0f88f851d4e9bb33c8430313c2e816f43))
* change getAsset to not return a promise ([#3232](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3232)) ([ab685e8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ab685e85943d1ac48142f157683bc2126fd6af16))
* cleanup nested widget validation ([#2991](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2991)) ([e4ba4d9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e4ba4d9d749c864e594c10e0bb31b0b8c4e6e60b))
* dispatch QUERY_FAILURE on query failure ([#3243](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3243)) ([2447f9c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2447f9c311db3c5db35ce6501c0380d304709d50))
* don't show duplicate entry when create is disabled ([#3162](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3162)) ([06c045e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/06c045e4e610d0578619ad0c7f787e41de769980))
* don't show progress when loading preview status ([#2974](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2974)) ([af61245](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/af6124536013e95b417501ef17f1144baffada72))
* duplicate and new entry action ([#3003](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3003)) ([9e7aa0c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9e7aa0c500f2bd394ca711846ec88c2b4fbf7ec5))
* handle missing inferred title field ([#3239](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3239)) ([ca8cf71](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ca8cf71ab0d479547c649fb1fce8e72db6207c27))
* sanitize dots in path collection config ([#3518](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3518)) ([601175c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/601175c6a146139718b3aba430deafe899896cae))
* set default public_folder on files and fields ([#3519](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3519)) ([1a577b8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1a577b8e2740a5e12a4c7cb543ed4e78312fc4b3))
* show better error for missing widgets ([#3377](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3377)) ([ff3b62d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ff3b62d12fc853fb3b712b7b33bf7064a6579a04))
* stop collection view controls from overflowing ([#3521](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3521)) ([c2425b4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c2425b44e86b5addaa4876ecee0e33dfa387c6f5))
* unify the title used in entry cards and workflow cards ([#3573](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3573)) ([#3575](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3575)) ([625a998](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/625a9980f1c113cb8e5159e42bfddfe94a0d6188))
* update error boundary about GitHub issue data ([#3471](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3471)) ([42d60a6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/42d60a644c58e01da72eb16c1cc20d93e0d70e13))
* use resolveBackend instead of currentBackend ([#3514](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3514)) ([ea41b98](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ea41b98324c61891d639df93cbf26148d6a93db6))
* use v1.1 schema only when parsing ([#3569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3569)) ([0761ffa](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0761ffa3f29c29a7b0c7cf56fdb38342bf25ff0e))
* **core:** custom widget validate bug in EditorControlPane ([#3435](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3435)) ([e81a35c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e81a35ccb8381c3132872f2d461134e1f4481080))
* **core:** force multiline flag for editor component patterns ([#3082](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3082)) ([476f450](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/476f45096efa1723936a73f2e2e04d5c7ccd293f))
* **core:** pass loadEntry to widgets as utility function and not redux action ([#3439](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3439)) ([6d87655](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6d8765521ca2f1b679b388b88b5101206c8f64f9))
* **core:** strip closing separators in yaml files ([#3198](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3198)) ([60ecc72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/60ecc72dfab660eea795fb1307df8596d65cd78b))
* **core:** use correct name for edit route param ([#3236](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3236)) ([cfd2fed](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cfd2fed494dc707e03ade086009ebfdd27578477))
* **locale:** remove hard coded strings ([#3193](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3193)) ([fc91bf8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/fc91bf8781e65ce1dc946363dbb10419a145c66b))
* don't wait for external media library to load ([#3050](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3050)) ([5bd7240](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5bd724026c8ebc08c56514f2c983d49c25c914ee))
* emotion use ref prop ([#2905](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2905)) ([9ddfa48](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9ddfa48512e54c77fc8e9a0f2eba4f0abf7c9029))
* keep editor slug path ([#2934](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2934)) ([3c4865f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3c4865f2a76e6b0f156ab801081251eb620495b2))
* load missing assets when retrieving backup ([#3192](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3192)) ([7d792f3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7d792f3005b1092c393c39ced90e2408fb43236b))
* load unpublished entries ([#2927](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2927)) ([caaa8b6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/caaa8b6db408623fd6001b9a8bad5d4711afbc76))
* media file path ([#3166](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3166)) ([d1179e3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d1179e3999cba5a022981042262c8e44e26c53d1))
* media library on reload ([#3174](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3174)) ([4f55442](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4f5544287fbd13be03794ec15bcfe992588290ed))
* rebase open authoring branches ([#2975](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2975)) ([8c175f6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8c175f6132fa18a13763cc563f7d3201c1e3580e))
* select widget dropdown options ([#2981](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2981)) ([9173d8c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9173d8c97e27a3742a25c36cc7cb11202c861385))
* **core:** use UTC date methods for slug formatting ([#2944](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2944)) ([d0b32a7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d0b32a7a0af62c08433f7d3ce0828214714ce28e))
* unpublish published entry ([#2931](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2931)) ([45a6ee9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/45a6ee92cc9322c57a3cd996b33c07d26c2d645e))
* **backend-github:** prepend collection name ([#2878](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2878)) ([465f463](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/465f4639597f258d5aa2c1b65e9d2c16023ee7ae))
* **backend-test-repo:** show notice when test repo is in use ([#2678](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2678)) ([c1c9587](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c1c95874f41bd2b435c39d3dea263c77eaa601eb))
* **deps:** update dependency react-is to v16.12.0 ([#2912](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2912)) ([695b0e0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/695b0e03805e7e1610787ec5f093499681bd3568))
* **deps:** update dependency react-polyglot to ^0.6.0 ([#2752](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2752)) ([ab5860f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ab5860f58ea15b69e860164986d7e24867d01954))
* **media-libs:** accept string or string array for insertMedia action ([#2857](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2857)) ([f5c8ff3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f5c8ff31f121e550f81b2472f2e3f0c8d76aab1b))
* **type-defs:** signature for CMS.registerWidget ([#3386](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3386)) ([9c0f618](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9c0f61814859f06759798601b05d80745e4197be))
* hide collection item overflow on hover ([#2706](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2706)) ([c54f896](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c54f896e3965e7d737cfca24fda283ab38d07982))
* prevent deletion of file collection entries by default ([#2627](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2627)) ([8bdfea4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8bdfea47287c7aef7dadee6fd5b8aa07bf00c9ac))
* **config:** strip leading slashes from collection location config ([#2131](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2131)) ([efa650c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/efa650ccf8786de6f65155ef47f6c9e98261f73b))
* **core:** allow updates through error boundary ([#2136](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2136)) ([3d98b72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3d98b72775a635c019c05e75976ff1a7f6d2e7d4))
* **core:** backend file system create entry ([#2401](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2401)) ([556c102](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/556c102e37e57ebbe9bc7b8c50714a9c769be0b1))
* **core:** correctly delete backups for new entries ([#2265](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2265)) ([a6c51fe](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a6c51fe14d7d3eec3a699bf31c7a8a3d206b8198))
* **core:** don't pass boolean value to string prop, use null instead ([#2609](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2609)) ([ce95a77](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ce95a774b2150c7b4b0fd74794da45215c68a0b2))
* **core:** don't pass ref to react-polyglot 'translate' function component ([#2607](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2607)) ([5b64e25](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5b64e25d073c80ccf709aa306b6f361b1a277fa9))
* **core:** ensure against slug overwrite ([#2139](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2139)) ([0ce995d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0ce995d78c8123a32a3e9ef7117fd5386f3cd02d))
* **core:** fix broken search ([#2488](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2488)) ([326ed4d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/326ed4dc3f9a6f0e29814e15c4b5a4b8367dc399))
* **core:** list widget default values ([#2374](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2374)) ([1806a2f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1806a2f0412ace84ea052e81108e31b176415cf0))
* **core:** list widget pattern validation ([#2599](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2599)) ([6765bbd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6765bbd2fd041a5aa8cee8033f6710d2262c37c4))
* **core:** load more entries until viewport is filled ([#2415](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2415)) ([a02496b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a02496b0dd6da1294ce49f3cb606251931d57ed0))
* **core:** number type slug template ([#2119](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2119)) ([7577443](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/75774438495e991fa0caa9e6d6133e3b86f9a724))
* **deps:** update dependency react-is to v16.8.5 ([#2232](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2232)) ([6e2d18f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6e2d18f671030f0f0fb7d960b48eed1a42c4a485))
* **deps:** update dependency react-polyglot to ^0.4.0 ([#2170](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2170)) ([d5248c8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d5248c8066daaa2ee9973fb0259a45d6d847ecd9))
* **deps:** update dependency react-scroll-sync to ^0.7.0 ([#2171](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2171)) ([12cc5a9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12cc5a99d3d4a975e4c9b16953efa0549495f40b))
* **deps:** update dependency react-sortable-hoc to v1 ([#2198](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2198)) ([b5180e9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b5180e96c3437174738358682146cb35a02086d9))
* **editorial-workflow:** fix LM pointers changing to binary files ([#2228](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2228)) ([d39a361](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d39a361e2dd149e9ab2cee06a93df8797c241314))
* **github-graphql:** use getMediaDisplayURL to load media with auth header ([#2652](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2652)) ([e674e43](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e674e43f9fe5c82256eb414c0ff85abf8e172387))
* **media-library:** automatically select uploaded image ([#2569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2569)) ([9f00310](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9f003106e5366511ab7fef8131e004bc17fcd8f5))
* **media-library:** no render of non-viewable files ([#2546](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2546)) ([4c5fe6a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4c5fe6a6061c8631e8dd03cf3959f0b254a13b9e))
* **netlify-cms-core:** validate nested fields ([#1873](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1873)) ([627e600](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/627e600d29584ed79387a098d91ada566d72c949))
* **widget-list:** validate string values in list widget ([#2385](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2385)) ([814aa50](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/814aa5091b977705913fb1c502e31a250f19874d))
* broken preview ([#2245](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2245)) ([4db497b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4db497b49696d4118f3cda06a244092c1a49fd17))
* export on netlify-cms and maps on esm ([#2244](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2244)) ([6ffd13b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6ffd13b946ac337096ed3e4c1ef253904acf3e39))
* fix umd builds ([#2214](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2214)) ([e04f6be](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e04f6bec1d24bd59c86ed095653f95d33dfc4297))
* redirect when a collection doesn't exist ([#2208](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2208)) ([9e08b65](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9e08b6550244877e2c71b08f72ad76c1e70e7176))
* update peer dep versions ([#2234](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2234)) ([7987091](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7987091196b644a0a70166183d480d62712af4f5))
* **a11y:** correct label "for" references to fields ([#1904](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1904)) ([955f94f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/955f94f72ba4d01473ba20f9e0bcf88e1e1467b9))
* **backend:** use singular label in custom commit message ([#1917](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1917)) ([2c5827b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2c5827bd99e740569a049dcdbe5eb7e85c668f69))
* **config:** allow setting publish_mode to 'simple' ([#1827](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1827)) ([288359d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/288359da3b0b6a1e03e2eec87b80848f1abca3c2))
* **config:** remove identifier field validation ([#1882](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1882)) ([fe6af19](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/fe6af1986fe522713753e2bf4217e43ed201a186))
* **config:** stop throwing on config.yml 404, fix manual init ([#1801](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1801)) ([d06c663](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d06c663778752e168f05a35da9fc46bfa9ae5c21))
* **gitlab:** fetch media library images through API ([#1433](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1433)) ([83d2adc](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/83d2adc0befccc04ec39c680591894a0e995d5b1))
* **i18n:** fix missing widget placeholder ([#1861](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1861)) ([b1a7e00](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b1a7e006f6af2b4e608e9028a4320cbecfcc7cc0))
* **list-widget:** fix single field usage in list widget ([#1395](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1395)) ([06d3650](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/06d3650faca5d06aac79782385ababc8604fb1fb))
* **netlify-cms-core:** allow arrays for frontmatter_delimiter in config ([#1997](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1997)) ([ebba686](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ebba686430a05980455eb5c463f0cbafa0ce44b9))
* **netlify-cms-core:** avoid leading replacement char in slug ([#1965](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1965)) ([79c0445](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/79c0445768481e15c401d8a179b5f73e77e18f69))
* **netlify-cms-core:** avoid partially loaded collection list ([#1964](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1964)) ([cedcbf8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cedcbf89a54e60ef2ff437106d72d94e765a2f7d))
* **netlify-cms-core:** duplicate key warning ([#1930](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1930)) ([9662eb2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9662eb292f4b0a0f21f4436445a57a5ef073ae80))
* **netlify-cms-core:** files collection blank label ([#1987](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1987)) ([f2e4800](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f2e4800989c10b956c43c4c617d81668ba3907bb))
* **netlify-cms-core:** fix collection entries loaded check ([#1881](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1881)) ([b374ffe](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b374ffe18b8e57297f64f18217abe88c5c69a6d9))
* **netlify-cms-core:** fix fields metadata for objects and lists ([#2011](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2011)) ([2d1d1c1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2d1d1c13df37aca701ff3b592aa6b2af5f4255ae))
* **netlify-cms-core:** fix identifier field validation ([#1907](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1907)) ([d5f4c99](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d5f4c99002521da4398a0ca53ab5d10759048a1d))
* **netlify-cms-core:** fix prop-types warnings ([#1906](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1906)) ([751ec09](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/751ec091fbf55c088e3bf8ed2e2a1d8f6240a550))
* **netlify-cms-core:** relation widget value swap ([#2018](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2018)) ([11305d3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/11305d36b2ea80a94e9e1a9bdbf3c20572292d65))
* **netlify-cms-core:** remove double focusable elements on profile menu button ([#1900](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1900)) ([888ae6b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/888ae6b053e386c39263f03c8c91f3b2d4967fd0))
* **netlify-cms-core:** support translation in error message ([#1935](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1935)) ([0f1ebd1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0f1ebd1060c79bc49f24abf2e3ee7781c8b5f72a))
* **netlify-cms-core:** workflow hide delete publish entry button ([#1971](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1971)) ([44fb2fb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/44fb2fb00dbc471cd3bb6c4026dc8ebc3288d04e))
* **widget-relation:** fix initial relation widget preview ([#2090](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2090)) ([aff9c1a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/aff9c1a70a43ebbbf5561ea543ca500b4d06eec0))
* bug fixes from linters ([#1524](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1524)) ([6632e5d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6632e5d1521cd3de0b357a54712ec0da36892c67))
* correct validation pattern error message ([#1879](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1879)) ([2a63940](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2a63940d979b3fe1ac1228977cde40395f4f56bf))
* fix App configError method ([#1864](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1864)) ([79205f7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/79205f7db320a755224ed9e0fabc82261e1409b5))
* fix entry saved message ([#1887](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1887)) ([c4e474b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c4e474b518763f50b737647c1153f83812ed5222))
* fix version console log ([#1528](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1528)) ([e82289b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e82289bff202f8dacd6bdf7166c2cb955425bcac))
* log accurate version by distribution ([#1531](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1531)) ([95a76ad](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/95a76ad7904f78433e994703b8a9239d5308a426))
* make media button consistent with links ([#1621](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1621)) ([412d1e6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/412d1e629f22d98c7806280780687fec016350ff))
* MediaLibraryHeader CloseButton style ([#1883](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1883)) ([034c29a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/034c29ad65d282f7f9ae75b7e991e9bf1f68482c))
* **relation:** fix relation widget selection bug ([#1572](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1572)) ([77fbc04](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/77fbc041bb24dfe254cd9c952e20ee84a32fa942))
* **widget-date:** fix default value for nested date widget ([#1859](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1859)) ([d8f8887](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d8f888706effcc46d602329523354570b65b11ed))
* **widgets:** fix list object field default values ([#1826](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1826)) ([c765793](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c765793971cd5f0c7cb947b643212d52e1616386))
* **workflow:** enable workflow per method ([#1569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1569)) ([90b8156](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/90b815657ea236e920200987115482d9b5cba615))
* only trim periods from file extensions ([#1554](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1554)) ([95c744e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/95c744ee3eedbb6d53c3d8cc171c385f82400bfa))
* **workflow:** fix status not set on new workflow entries ([#1558](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1558)) ([0aa085f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0aa085f8d29d6077f292796f6762eff852d6e3e3))
* **workflow:** label file collection entries in Workflow ([#2566](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2566)) ([542a7ac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/542a7acfe60719f30bbb1ec8da37f6a498194400))


### Features

* adds ability to specify alternate options for select widget ([d4ceed7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d4ceed79bf2a5c42b521357d0e4dfed1193fce2f))
* **widget-relation:** string templates support ([#3659](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3659)) ([213ae86](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/213ae86b54d02f5fc79fe11113507587ed062ff2))
* add cloudinary support ([#1932](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1932)) ([1fc2f50](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1fc2f50499e0311eac033dcfce321e1106c4713b))
* add entry, collection and config prop to control widget ([#3672](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3672)) ([3e5ff71](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3e5ff7184604fd1f18a01c7223d0dc5d199f0eac))
* add hide property to collections ([#3618](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3618)) ([#3643](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3643)) ([88b6c63](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/88b6c633afb4ba50fe46c0fef753bd209f832e67))
* add prePublish,postPublish events ([#3172](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3172)) ([0d7e36b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0d7e36ba7952b1353b5a5bc4417994d45596a9a1))
* add-download-button closes [#3429](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3429) ([#3609](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3609)) ([cf25260](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cf252605ad8fee6f3d307302dc50759813ee765c))
* **yaml:** support comments ([#3529](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3529)) ([4afbbdd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4afbbdd8a99241d239f28c5be544bb0ca77e345b))
* Add 'hero' as inferable image field ([#3294](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3294)) ([971926c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/971926c36941694acdc37649494f1f62f3f5f40e))
* add ES module builds ([#2215](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2215)) ([d142b32](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d142b32345ea7c63e081a1c43086786fe737d566))
* add media lib virtualization ([#3381](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3381)) ([92e7601](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/92e76011e7a9e8b5370088b0a2c065df66b5f7fb))
* add preUnpublish, postUnpublish events ([#3196](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3196)) ([18e284e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18e284ece83fb6ae07a953dbdefe347bc48d4acc))
* add publish configuration option to collections ([#3467](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3467)) ([df33bc6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/df33bc64a996eedcb10835064a7cab8e7862e94d))
* add translation support ([#2870](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2870)) ([096b067](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/096b067d4542c723630ded631fc9a4ba950732f3)), closes [#2877](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2877)
* allow custom logo on auth page ([#1818](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1818)) ([c6ae1e8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c6ae1e8fc0ae1fe0d228b281401ed1cf6a1f2895))
* bundle assets with content ([#2958](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2958)) ([2b41d8a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2b41d8a838a9c8a6b21cde2ddd16b9288334e298))
* Code Widget + Markdown Widget Internal Overhaul ([#2828](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2828)) ([18c579d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18c579d0e9f0ff71ed8c52f5c66f2309259af054))
* commit media with post ([#2851](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2851)) ([6515dee](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6515dee8715d8571ea19484a7dfab7cfd0cc40be))
* content in sub folders ([#2897](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2897)) ([afcfe5b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/afcfe5b6d5f32669e9061ec596bd35ad545d61a3))
* duplicate entry ([#2956](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2956)) ([d180bff](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d180bffb44432a82f2b4e5a08df5693b30268fee))
* enable specifying custom open authoring commit message ([#2810](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2810)) ([2841ff9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2841ff9ffe58afcf4dba45514a84a262ad370f1d))
* field based media/public folders ([#3208](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3208)) ([97bc0c8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/97bc0c8dc489e736f89d748ba832d78400fe4332))
* populate new entry from URL params ([#3343](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3343)) ([e0b1246](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e0b124681093c6f1dff9b9ec0ffab835716e66b5))
* sanitize media filenames according to global slug setting ([#3315](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3315)) ([8874769](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8874769b317e6e364c881039c0c9308826f49cff))
* support filename and extension vars in summary ([#3375](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3375)) ([12444ca](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12444ca761d5cd40d766847f117e55b0e0ca6e9e))
* **backend-git-gateway:** handle identity disabled error message ([#3002](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3002)) ([b5ffccd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b5ffccdac506db416c09aaebb38611783487c52a))
* **core:** allow custom summary on entry cards ([#2140](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2140)) ([573ad88](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/573ad8816d93fa8c7d8636dd130e009b5616ab23))
* **core:** allow field name to override slug placeholders ([#2087](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2087)) ([ff8dfac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ff8dfac813eefca82a53670454ca359c50ad43b2))
* **core:** auto detect proxy server on load ([#3195](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3195)) ([614f1ae](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/614f1aea63de672a89dc55d485ad0302bc1f1bf2))
* **core:** recover entry after unexpected quit ([#2129](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2129)) ([686504a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/686504adee2c29319fc0119c572a54e21c114be6))
* **proxy-server:** add local fs middleware and make it the default ([#3217](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3217)) ([31dbd72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/31dbd72273b723bb6bbb551641a6e4bcc1f0314b))
* provide usable UMD builds for all packages ([#2141](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2141)) ([82cc794](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/82cc7941cc40d31ead6eab40d7a9d999471399a5))
* support per collection public_folder ([#3069](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3069)) ([0a50efd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0a50efda8e5a9e5cc99291890e3eab2307266c56))
* upgrade to Emotion 10 ([#2166](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2166)) ([ccef446](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ccef446d72f96fa8d8db9bf2d0be5633eff79979))
* workflow unpublished entry ([#2914](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2914)) ([41bb9aa](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/41bb9aac0dd6fd9f8ff157bb0b29c85aa87fe04d))
* **backend-github:** Open Authoring ([#2430](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2430)) ([edf0a3a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/edf0a3afdc01690c9075476354db7a6b46e84f16))
* **config:** add support for setting custom identifier field ([#1543](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1543)) ([12418dd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12418dd7f07f3e27218421838407b6252988fb43))
* **config:** allow config.yml file load to be skipped ([#2053](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2053)) ([14f94a0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/14f94a022ce137efc7e4498e4d638333520154cb))
* **editor:** display optional status in widget labels ([#1955](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1955)) ([44b7cdf](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/44b7cdf9f88334024e358d8b2288b9d122a06b6b))
* **media:** add external media library support, Uploadcare integration ([#1602](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1602)) ([0596904](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0596904e0b850d2ac9b15bd1a4055b392f36c819))
* **netlify-cms-core:** expose loadEntry action to Widgets ([#2010](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2010)) ([5d8aef1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5d8aef1d948be0664d787cc0d5a2e7d207909ede))
* **netlify-cms-widget-map:** add map widget ([#2051](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2051)) ([18f34d2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18f34d2acaea396a9fb444856d3fd324533791a5))
* **netlify-cms-widget-relation:** use react-select and add support for multiple entries ([#1936](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1936)) ([518f6fb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/518f6fb1c070cbfc513e8a3170bf57dc25dbd18d))
* **netlify-cms-widget-select:** add support for multiple selection ([#1901](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1901)) ([88bf287](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/88bf2872212779b4a23ea4e1a3e0213f70a8eaa9))
* **routing:** support direct linking to entries ([#2556](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2556)) ([083a336](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/083a336ba48a99c9844119c7215ebf4d4c562938))
* **widget-number:** add range validation ([#2049](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2049)) ([dc44cac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/dc44caca20c46a1215736069d68c2888ce53669b))
* **widget-relation:** support nested field references in relation widget ([#2391](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2391)) ([d6964b5](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d6964b50b3ea742ef1d4ed7c4b2032225790ab3c))
* **workflow:** add deploy preview links ([#2028](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2028)) ([15d221d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/15d221d4a4d16b795893441108cfc05909ca347a))


### Reverts

* Revert "chore(release): publish" ([a015d1d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a015d1d92a4b1c0130c44fcef1c9ecdb157a0f07))
* don't force multiline flag for editor component patterns ([#3089](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3089)) ([c4cbae7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c4cbae77255d1f422fd62258a01007956d512392))





# 2.25.0-beta.0 (2020-05-03)


### Bug Fixes

* add missing generic type to registerPreviewTemplate ([#3597](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3597)) ([36ae69c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/36ae69c96eded5f4af4a9bd63e319f64b62b0e63))
* allow unlimited alias count ([#3570](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3570)) ([bfb2e2b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/bfb2e2bc574d9b356aa14ffb3b6eb7eca285c73a))
* allow widgets to control value to be validated ([#3448](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3448)) ([ae1917c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ae1917c8181892a439d0828d98992788fb48d65c))
* cache assets using resolved path on error ([#3378](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3378)) ([f3fd43b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f3fd43b81928abaea99b50ee4223de3c0498cb71))
* call createDraftFromEntry after entry is loaded instead in Editor ([#3418](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3418)) ([2409323](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2409323dba1abe8a670d18453369fd75c6e240fb))
* change default open authoring scope, make it configurable ([#2821](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2821)) ([002cdd7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/002cdd77a856bde3672e75dde6d3a2b246e1035f))
* consider variable types when traversing collection fields ([#3347](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3347)) ([961cde4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/961cde4ea523027a1367bbdb84adbc2843a79b57))
* don't override empty public folder ([#3513](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3513)) ([a1bf86e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a1bf86e8566dfad123926339b16d9a16a4bfd77a))
* don't use getAsset for draft entries ([#3403](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3403)) ([45a1654](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/45a1654404ef7bd24dd2f04a4b3f896d1eef0b7d))
* dupe entry declaration ([029f13b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/029f13b7d9387b7567696e19538c6a6ff72136c3))
* dupe entry declaration ([97f3aca](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/97f3aca412e33cccbcd00e3e33eada9575e5c345))
* duplicate entry ([#3563](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3563)) ([1d88b15](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1d88b15de54d62d1d8d40a0391e9fc640af2ca97))
* enable merge option for yaml parser ([#3577](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3577)) ([b8eeab2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b8eeab2e35a51cb8128d2a0df23d8ecd489208cd))
* ensure draft changes ([#3306](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3306)) ([cf81f58](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cf81f587cf517b2906e261e89090de984aad3ce3))
* esm extensions ([eff4b28](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/eff4b285265e4698e7e842abc11673810409dfbc))
* ja locale labels ([#3367](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3367)) ([50837b0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/50837b0068ac8972ce16cbf5f238aa5a2c5bd6e9))
* media files when duplicating entry ([#3507](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3507)) ([9705295](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/970529570b11bbcf3fb65e91f2be09b699b20be7))
* missing widgets ([#3541](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3541)) ([6933bf6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6933bf6ee1acbbefb2cc7840a8aef6accc2d455b))
* pass prettyErrors to yaml when parsing config ([#3571](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3571)) ([0d59642](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0d59642e64e9341b3ac73ede4cfb0e4ba2980faa))
* preserve unknown fields value ([#3314](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3314)) ([908c42f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/908c42fb588ce87f4e197df65db2d238f34837f4))
* redirect to default path after login success if url has prev error ([#3599](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3599)) ([bb0a7e9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/bb0a7e96d82d950735eafce3017460caf0fd6d0c))
* sidebar icon shrinking when label wraps ([#3653](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3653)) ([a9d0699](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a9d0699a82a25d79dd99af4f1ed9643ce7bba220))
* support common backend configuration options from docs in ts types ([#3674](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3674)) ([2580251](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/25802512087854e23333837d48a284832d9d50b2))
* **backend-github:** improve workflow migration edge cases/messaging ([#3319](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3319)) ([684b79e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/684b79e43bebb63ce1e844eae5c8c0e76087687b))
* **core:** improve editor buttons for smaller screens ([#3327](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3327)) ([53365b7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/53365b73701c872948a1e65da00a655e0718e8cb))
* **core:** report config error when external media lib is missing ([#3255](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3255)) ([1d63038](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1d63038e78a6db1e7a061b5ba447f951d892595a))
* **sort:** don't clear sort data on entries request ([#3648](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3648)) ([cf57284](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cf57284f40141712e3265992bdf6966a5c81f838))
* **type-defs:**  add string type to EditorComponentData id property ([#3602](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3602)) ([1a60e6d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1a60e6d7fde3c282df23487cd1f7479b0b848873))
* **types:** instead of the inferred {}, allow any kind of props ([#3638](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3638)) ([3f72f43](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3f72f438a1e2ad1111780208af69bf172becd277))
* .d.ts definitions for core and app ([#2929](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2929)) ([7391061](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7391061b3b8b1971b994f497a6df29b7d5c3da74))
* allow absolute paths for collection media folder ([#3160](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3160)) ([a215cfb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a215cfbe3aa875fb932878039a5efbde6d97b538))
* always ensure collection exists before routing ([#2992](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2992)) ([982fd7b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/982fd7b0f88f851d4e9bb33c8430313c2e816f43))
* change getAsset to not return a promise ([#3232](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3232)) ([ab685e8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ab685e85943d1ac48142f157683bc2126fd6af16))
* cleanup nested widget validation ([#2991](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2991)) ([e4ba4d9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e4ba4d9d749c864e594c10e0bb31b0b8c4e6e60b))
* dispatch QUERY_FAILURE on query failure ([#3243](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3243)) ([2447f9c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2447f9c311db3c5db35ce6501c0380d304709d50))
* don't show duplicate entry when create is disabled ([#3162](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3162)) ([06c045e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/06c045e4e610d0578619ad0c7f787e41de769980))
* don't show progress when loading preview status ([#2974](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2974)) ([af61245](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/af6124536013e95b417501ef17f1144baffada72))
* duplicate and new entry action ([#3003](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3003)) ([9e7aa0c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9e7aa0c500f2bd394ca711846ec88c2b4fbf7ec5))
* handle missing inferred title field ([#3239](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3239)) ([ca8cf71](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ca8cf71ab0d479547c649fb1fce8e72db6207c27))
* sanitize dots in path collection config ([#3518](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3518)) ([601175c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/601175c6a146139718b3aba430deafe899896cae))
* set default public_folder on files and fields ([#3519](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3519)) ([1a577b8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1a577b8e2740a5e12a4c7cb543ed4e78312fc4b3))
* show better error for missing widgets ([#3377](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3377)) ([ff3b62d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ff3b62d12fc853fb3b712b7b33bf7064a6579a04))
* stop collection view controls from overflowing ([#3521](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3521)) ([c2425b4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c2425b44e86b5addaa4876ecee0e33dfa387c6f5))
* unify the title used in entry cards and workflow cards ([#3573](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3573)) ([#3575](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3575)) ([625a998](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/625a9980f1c113cb8e5159e42bfddfe94a0d6188))
* update error boundary about GitHub issue data ([#3471](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3471)) ([42d60a6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/42d60a644c58e01da72eb16c1cc20d93e0d70e13))
* use resolveBackend instead of currentBackend ([#3514](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3514)) ([ea41b98](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ea41b98324c61891d639df93cbf26148d6a93db6))
* use v1.1 schema only when parsing ([#3569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3569)) ([0761ffa](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0761ffa3f29c29a7b0c7cf56fdb38342bf25ff0e))
* **core:** custom widget validate bug in EditorControlPane ([#3435](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3435)) ([e81a35c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e81a35ccb8381c3132872f2d461134e1f4481080))
* **core:** force multiline flag for editor component patterns ([#3082](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3082)) ([476f450](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/476f45096efa1723936a73f2e2e04d5c7ccd293f))
* **core:** pass loadEntry to widgets as utility function and not redux action ([#3439](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3439)) ([6d87655](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6d8765521ca2f1b679b388b88b5101206c8f64f9))
* **core:** strip closing separators in yaml files ([#3198](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3198)) ([60ecc72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/60ecc72dfab660eea795fb1307df8596d65cd78b))
* **core:** use correct name for edit route param ([#3236](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3236)) ([cfd2fed](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cfd2fed494dc707e03ade086009ebfdd27578477))
* **locale:** remove hard coded strings ([#3193](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3193)) ([fc91bf8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/fc91bf8781e65ce1dc946363dbb10419a145c66b))
* don't wait for external media library to load ([#3050](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3050)) ([5bd7240](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5bd724026c8ebc08c56514f2c983d49c25c914ee))
* emotion use ref prop ([#2905](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2905)) ([9ddfa48](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9ddfa48512e54c77fc8e9a0f2eba4f0abf7c9029))
* keep editor slug path ([#2934](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2934)) ([3c4865f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3c4865f2a76e6b0f156ab801081251eb620495b2))
* load missing assets when retrieving backup ([#3192](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3192)) ([7d792f3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7d792f3005b1092c393c39ced90e2408fb43236b))
* load unpublished entries ([#2927](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2927)) ([caaa8b6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/caaa8b6db408623fd6001b9a8bad5d4711afbc76))
* media file path ([#3166](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3166)) ([d1179e3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d1179e3999cba5a022981042262c8e44e26c53d1))
* media library on reload ([#3174](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3174)) ([4f55442](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4f5544287fbd13be03794ec15bcfe992588290ed))
* rebase open authoring branches ([#2975](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2975)) ([8c175f6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8c175f6132fa18a13763cc563f7d3201c1e3580e))
* select widget dropdown options ([#2981](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2981)) ([9173d8c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9173d8c97e27a3742a25c36cc7cb11202c861385))
* **core:** use UTC date methods for slug formatting ([#2944](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2944)) ([d0b32a7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d0b32a7a0af62c08433f7d3ce0828214714ce28e))
* unpublish published entry ([#2931](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2931)) ([45a6ee9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/45a6ee92cc9322c57a3cd996b33c07d26c2d645e))
* **backend-github:** prepend collection name ([#2878](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2878)) ([465f463](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/465f4639597f258d5aa2c1b65e9d2c16023ee7ae))
* **backend-test-repo:** show notice when test repo is in use ([#2678](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2678)) ([c1c9587](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c1c95874f41bd2b435c39d3dea263c77eaa601eb))
* **deps:** update dependency react-is to v16.12.0 ([#2912](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2912)) ([695b0e0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/695b0e03805e7e1610787ec5f093499681bd3568))
* **deps:** update dependency react-polyglot to ^0.6.0 ([#2752](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2752)) ([ab5860f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ab5860f58ea15b69e860164986d7e24867d01954))
* **media-libs:** accept string or string array for insertMedia action ([#2857](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2857)) ([f5c8ff3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f5c8ff31f121e550f81b2472f2e3f0c8d76aab1b))
* **type-defs:** signature for CMS.registerWidget ([#3386](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3386)) ([9c0f618](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9c0f61814859f06759798601b05d80745e4197be))
* hide collection item overflow on hover ([#2706](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2706)) ([c54f896](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c54f896e3965e7d737cfca24fda283ab38d07982))
* prevent deletion of file collection entries by default ([#2627](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2627)) ([8bdfea4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8bdfea47287c7aef7dadee6fd5b8aa07bf00c9ac))
* **config:** strip leading slashes from collection location config ([#2131](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2131)) ([efa650c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/efa650ccf8786de6f65155ef47f6c9e98261f73b))
* **core:** allow updates through error boundary ([#2136](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2136)) ([3d98b72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3d98b72775a635c019c05e75976ff1a7f6d2e7d4))
* **core:** backend file system create entry ([#2401](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2401)) ([556c102](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/556c102e37e57ebbe9bc7b8c50714a9c769be0b1))
* **core:** correctly delete backups for new entries ([#2265](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2265)) ([a6c51fe](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a6c51fe14d7d3eec3a699bf31c7a8a3d206b8198))
* **core:** don't pass boolean value to string prop, use null instead ([#2609](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2609)) ([ce95a77](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ce95a774b2150c7b4b0fd74794da45215c68a0b2))
* **core:** don't pass ref to react-polyglot 'translate' function component ([#2607](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2607)) ([5b64e25](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5b64e25d073c80ccf709aa306b6f361b1a277fa9))
* **core:** ensure against slug overwrite ([#2139](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2139)) ([0ce995d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0ce995d78c8123a32a3e9ef7117fd5386f3cd02d))
* **core:** fix broken search ([#2488](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2488)) ([326ed4d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/326ed4dc3f9a6f0e29814e15c4b5a4b8367dc399))
* **core:** list widget default values ([#2374](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2374)) ([1806a2f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1806a2f0412ace84ea052e81108e31b176415cf0))
* **core:** list widget pattern validation ([#2599](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2599)) ([6765bbd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6765bbd2fd041a5aa8cee8033f6710d2262c37c4))
* **core:** load more entries until viewport is filled ([#2415](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2415)) ([a02496b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a02496b0dd6da1294ce49f3cb606251931d57ed0))
* **core:** number type slug template ([#2119](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2119)) ([7577443](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/75774438495e991fa0caa9e6d6133e3b86f9a724))
* **deps:** update dependency react-is to v16.8.5 ([#2232](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2232)) ([6e2d18f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6e2d18f671030f0f0fb7d960b48eed1a42c4a485))
* **deps:** update dependency react-polyglot to ^0.4.0 ([#2170](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2170)) ([d5248c8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d5248c8066daaa2ee9973fb0259a45d6d847ecd9))
* **deps:** update dependency react-scroll-sync to ^0.7.0 ([#2171](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2171)) ([12cc5a9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12cc5a99d3d4a975e4c9b16953efa0549495f40b))
* **deps:** update dependency react-sortable-hoc to v1 ([#2198](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2198)) ([b5180e9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b5180e96c3437174738358682146cb35a02086d9))
* **editorial-workflow:** fix LM pointers changing to binary files ([#2228](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2228)) ([d39a361](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d39a361e2dd149e9ab2cee06a93df8797c241314))
* **github-graphql:** use getMediaDisplayURL to load media with auth header ([#2652](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2652)) ([e674e43](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e674e43f9fe5c82256eb414c0ff85abf8e172387))
* **media-library:** automatically select uploaded image ([#2569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2569)) ([9f00310](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9f003106e5366511ab7fef8131e004bc17fcd8f5))
* **media-library:** no render of non-viewable files ([#2546](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2546)) ([4c5fe6a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4c5fe6a6061c8631e8dd03cf3959f0b254a13b9e))
* **netlify-cms-core:** validate nested fields ([#1873](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1873)) ([627e600](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/627e600d29584ed79387a098d91ada566d72c949))
* **widget-list:** validate string values in list widget ([#2385](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2385)) ([814aa50](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/814aa5091b977705913fb1c502e31a250f19874d))
* broken preview ([#2245](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2245)) ([4db497b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4db497b49696d4118f3cda06a244092c1a49fd17))
* export on netlify-cms and maps on esm ([#2244](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2244)) ([6ffd13b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6ffd13b946ac337096ed3e4c1ef253904acf3e39))
* fix umd builds ([#2214](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2214)) ([e04f6be](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e04f6bec1d24bd59c86ed095653f95d33dfc4297))
* redirect when a collection doesn't exist ([#2208](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2208)) ([9e08b65](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9e08b6550244877e2c71b08f72ad76c1e70e7176))
* update peer dep versions ([#2234](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2234)) ([7987091](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7987091196b644a0a70166183d480d62712af4f5))
* **a11y:** correct label "for" references to fields ([#1904](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1904)) ([955f94f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/955f94f72ba4d01473ba20f9e0bcf88e1e1467b9))
* **backend:** use singular label in custom commit message ([#1917](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1917)) ([2c5827b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2c5827bd99e740569a049dcdbe5eb7e85c668f69))
* **config:** allow setting publish_mode to 'simple' ([#1827](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1827)) ([288359d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/288359da3b0b6a1e03e2eec87b80848f1abca3c2))
* **config:** remove identifier field validation ([#1882](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1882)) ([fe6af19](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/fe6af1986fe522713753e2bf4217e43ed201a186))
* **config:** stop throwing on config.yml 404, fix manual init ([#1801](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1801)) ([d06c663](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d06c663778752e168f05a35da9fc46bfa9ae5c21))
* **gitlab:** fetch media library images through API ([#1433](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1433)) ([83d2adc](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/83d2adc0befccc04ec39c680591894a0e995d5b1))
* **i18n:** fix missing widget placeholder ([#1861](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1861)) ([b1a7e00](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b1a7e006f6af2b4e608e9028a4320cbecfcc7cc0))
* **list-widget:** fix single field usage in list widget ([#1395](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1395)) ([06d3650](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/06d3650faca5d06aac79782385ababc8604fb1fb))
* **netlify-cms-core:** allow arrays for frontmatter_delimiter in config ([#1997](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1997)) ([ebba686](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ebba686430a05980455eb5c463f0cbafa0ce44b9))
* **netlify-cms-core:** avoid leading replacement char in slug ([#1965](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1965)) ([79c0445](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/79c0445768481e15c401d8a179b5f73e77e18f69))
* **netlify-cms-core:** avoid partially loaded collection list ([#1964](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1964)) ([cedcbf8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cedcbf89a54e60ef2ff437106d72d94e765a2f7d))
* **netlify-cms-core:** duplicate key warning ([#1930](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1930)) ([9662eb2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9662eb292f4b0a0f21f4436445a57a5ef073ae80))
* **netlify-cms-core:** files collection blank label ([#1987](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1987)) ([f2e4800](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f2e4800989c10b956c43c4c617d81668ba3907bb))
* **netlify-cms-core:** fix collection entries loaded check ([#1881](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1881)) ([b374ffe](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b374ffe18b8e57297f64f18217abe88c5c69a6d9))
* **netlify-cms-core:** fix fields metadata for objects and lists ([#2011](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2011)) ([2d1d1c1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2d1d1c13df37aca701ff3b592aa6b2af5f4255ae))
* **netlify-cms-core:** fix identifier field validation ([#1907](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1907)) ([d5f4c99](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d5f4c99002521da4398a0ca53ab5d10759048a1d))
* **netlify-cms-core:** fix prop-types warnings ([#1906](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1906)) ([751ec09](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/751ec091fbf55c088e3bf8ed2e2a1d8f6240a550))
* **netlify-cms-core:** relation widget value swap ([#2018](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2018)) ([11305d3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/11305d36b2ea80a94e9e1a9bdbf3c20572292d65))
* **netlify-cms-core:** remove double focusable elements on profile menu button ([#1900](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1900)) ([888ae6b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/888ae6b053e386c39263f03c8c91f3b2d4967fd0))
* **netlify-cms-core:** support translation in error message ([#1935](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1935)) ([0f1ebd1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0f1ebd1060c79bc49f24abf2e3ee7781c8b5f72a))
* **netlify-cms-core:** workflow hide delete publish entry button ([#1971](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1971)) ([44fb2fb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/44fb2fb00dbc471cd3bb6c4026dc8ebc3288d04e))
* **widget-relation:** fix initial relation widget preview ([#2090](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2090)) ([aff9c1a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/aff9c1a70a43ebbbf5561ea543ca500b4d06eec0))
* bug fixes from linters ([#1524](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1524)) ([6632e5d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6632e5d1521cd3de0b357a54712ec0da36892c67))
* correct validation pattern error message ([#1879](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1879)) ([2a63940](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2a63940d979b3fe1ac1228977cde40395f4f56bf))
* fix App configError method ([#1864](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1864)) ([79205f7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/79205f7db320a755224ed9e0fabc82261e1409b5))
* fix entry saved message ([#1887](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1887)) ([c4e474b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c4e474b518763f50b737647c1153f83812ed5222))
* fix version console log ([#1528](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1528)) ([e82289b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e82289bff202f8dacd6bdf7166c2cb955425bcac))
* log accurate version by distribution ([#1531](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1531)) ([95a76ad](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/95a76ad7904f78433e994703b8a9239d5308a426))
* make media button consistent with links ([#1621](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1621)) ([412d1e6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/412d1e629f22d98c7806280780687fec016350ff))
* MediaLibraryHeader CloseButton style ([#1883](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1883)) ([034c29a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/034c29ad65d282f7f9ae75b7e991e9bf1f68482c))
* **relation:** fix relation widget selection bug ([#1572](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1572)) ([77fbc04](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/77fbc041bb24dfe254cd9c952e20ee84a32fa942))
* **widget-date:** fix default value for nested date widget ([#1859](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1859)) ([d8f8887](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d8f888706effcc46d602329523354570b65b11ed))
* **widgets:** fix list object field default values ([#1826](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1826)) ([c765793](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c765793971cd5f0c7cb947b643212d52e1616386))
* **workflow:** enable workflow per method ([#1569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1569)) ([90b8156](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/90b815657ea236e920200987115482d9b5cba615))
* only trim periods from file extensions ([#1554](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1554)) ([95c744e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/95c744ee3eedbb6d53c3d8cc171c385f82400bfa))
* **workflow:** fix status not set on new workflow entries ([#1558](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1558)) ([0aa085f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0aa085f8d29d6077f292796f6762eff852d6e3e3))
* **workflow:** label file collection entries in Workflow ([#2566](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2566)) ([542a7ac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/542a7acfe60719f30bbb1ec8da37f6a498194400))


### Features

* adds ability to specify alternate options for select widget ([d4ceed7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d4ceed79bf2a5c42b521357d0e4dfed1193fce2f))
* **widget-relation:** string templates support ([#3659](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3659)) ([213ae86](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/213ae86b54d02f5fc79fe11113507587ed062ff2))
* add cloudinary support ([#1932](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1932)) ([1fc2f50](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1fc2f50499e0311eac033dcfce321e1106c4713b))
* add entry, collection and config prop to control widget ([#3672](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3672)) ([3e5ff71](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3e5ff7184604fd1f18a01c7223d0dc5d199f0eac))
* add hide property to collections ([#3618](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3618)) ([#3643](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3643)) ([88b6c63](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/88b6c633afb4ba50fe46c0fef753bd209f832e67))
* add prePublish,postPublish events ([#3172](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3172)) ([0d7e36b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0d7e36ba7952b1353b5a5bc4417994d45596a9a1))
* add-download-button closes [#3429](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3429) ([#3609](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3609)) ([cf25260](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cf252605ad8fee6f3d307302dc50759813ee765c))
* **yaml:** support comments ([#3529](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3529)) ([4afbbdd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4afbbdd8a99241d239f28c5be544bb0ca77e345b))
* Add 'hero' as inferable image field ([#3294](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3294)) ([971926c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/971926c36941694acdc37649494f1f62f3f5f40e))
* add ES module builds ([#2215](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2215)) ([d142b32](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d142b32345ea7c63e081a1c43086786fe737d566))
* add media lib virtualization ([#3381](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3381)) ([92e7601](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/92e76011e7a9e8b5370088b0a2c065df66b5f7fb))
* add preUnpublish, postUnpublish events ([#3196](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3196)) ([18e284e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18e284ece83fb6ae07a953dbdefe347bc48d4acc))
* add publish configuration option to collections ([#3467](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3467)) ([df33bc6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/df33bc64a996eedcb10835064a7cab8e7862e94d))
* add translation support ([#2870](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2870)) ([096b067](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/096b067d4542c723630ded631fc9a4ba950732f3)), closes [#2877](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2877)
* allow custom logo on auth page ([#1818](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1818)) ([c6ae1e8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c6ae1e8fc0ae1fe0d228b281401ed1cf6a1f2895))
* bundle assets with content ([#2958](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2958)) ([2b41d8a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2b41d8a838a9c8a6b21cde2ddd16b9288334e298))
* Code Widget + Markdown Widget Internal Overhaul ([#2828](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2828)) ([18c579d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18c579d0e9f0ff71ed8c52f5c66f2309259af054))
* commit media with post ([#2851](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2851)) ([6515dee](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6515dee8715d8571ea19484a7dfab7cfd0cc40be))
* content in sub folders ([#2897](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2897)) ([afcfe5b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/afcfe5b6d5f32669e9061ec596bd35ad545d61a3))
* duplicate entry ([#2956](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2956)) ([d180bff](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d180bffb44432a82f2b4e5a08df5693b30268fee))
* enable specifying custom open authoring commit message ([#2810](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2810)) ([2841ff9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2841ff9ffe58afcf4dba45514a84a262ad370f1d))
* field based media/public folders ([#3208](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3208)) ([97bc0c8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/97bc0c8dc489e736f89d748ba832d78400fe4332))
* populate new entry from URL params ([#3343](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3343)) ([e0b1246](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e0b124681093c6f1dff9b9ec0ffab835716e66b5))
* sanitize media filenames according to global slug setting ([#3315](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3315)) ([8874769](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8874769b317e6e364c881039c0c9308826f49cff))
* support filename and extension vars in summary ([#3375](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3375)) ([12444ca](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12444ca761d5cd40d766847f117e55b0e0ca6e9e))
* **backend-git-gateway:** handle identity disabled error message ([#3002](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3002)) ([b5ffccd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b5ffccdac506db416c09aaebb38611783487c52a))
* **core:** allow custom summary on entry cards ([#2140](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2140)) ([573ad88](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/573ad8816d93fa8c7d8636dd130e009b5616ab23))
* **core:** allow field name to override slug placeholders ([#2087](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2087)) ([ff8dfac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ff8dfac813eefca82a53670454ca359c50ad43b2))
* **core:** auto detect proxy server on load ([#3195](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3195)) ([614f1ae](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/614f1aea63de672a89dc55d485ad0302bc1f1bf2))
* **core:** recover entry after unexpected quit ([#2129](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2129)) ([686504a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/686504adee2c29319fc0119c572a54e21c114be6))
* **proxy-server:** add local fs middleware and make it the default ([#3217](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3217)) ([31dbd72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/31dbd72273b723bb6bbb551641a6e4bcc1f0314b))
* provide usable UMD builds for all packages ([#2141](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2141)) ([82cc794](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/82cc7941cc40d31ead6eab40d7a9d999471399a5))
* support per collection public_folder ([#3069](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3069)) ([0a50efd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0a50efda8e5a9e5cc99291890e3eab2307266c56))
* upgrade to Emotion 10 ([#2166](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2166)) ([ccef446](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ccef446d72f96fa8d8db9bf2d0be5633eff79979))
* workflow unpublished entry ([#2914](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2914)) ([41bb9aa](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/41bb9aac0dd6fd9f8ff157bb0b29c85aa87fe04d))
* **backend-github:** Open Authoring ([#2430](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2430)) ([edf0a3a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/edf0a3afdc01690c9075476354db7a6b46e84f16))
* **config:** add support for setting custom identifier field ([#1543](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1543)) ([12418dd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12418dd7f07f3e27218421838407b6252988fb43))
* **config:** allow config.yml file load to be skipped ([#2053](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2053)) ([14f94a0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/14f94a022ce137efc7e4498e4d638333520154cb))
* **editor:** display optional status in widget labels ([#1955](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1955)) ([44b7cdf](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/44b7cdf9f88334024e358d8b2288b9d122a06b6b))
* **media:** add external media library support, Uploadcare integration ([#1602](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1602)) ([0596904](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0596904e0b850d2ac9b15bd1a4055b392f36c819))
* **netlify-cms-core:** expose loadEntry action to Widgets ([#2010](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2010)) ([5d8aef1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5d8aef1d948be0664d787cc0d5a2e7d207909ede))
* **netlify-cms-widget-map:** add map widget ([#2051](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2051)) ([18f34d2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18f34d2acaea396a9fb444856d3fd324533791a5))
* **netlify-cms-widget-relation:** use react-select and add support for multiple entries ([#1936](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1936)) ([518f6fb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/518f6fb1c070cbfc513e8a3170bf57dc25dbd18d))
* **netlify-cms-widget-select:** add support for multiple selection ([#1901](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1901)) ([88bf287](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/88bf2872212779b4a23ea4e1a3e0213f70a8eaa9))
* **routing:** support direct linking to entries ([#2556](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2556)) ([083a336](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/083a336ba48a99c9844119c7215ebf4d4c562938))
* **widget-number:** add range validation ([#2049](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2049)) ([dc44cac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/dc44caca20c46a1215736069d68c2888ce53669b))
* **widget-relation:** support nested field references in relation widget ([#2391](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2391)) ([d6964b5](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d6964b50b3ea742ef1d4ed7c4b2032225790ab3c))
* **workflow:** add deploy preview links ([#2028](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2028)) ([15d221d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/15d221d4a4d16b795893441108cfc05909ca347a))


### Reverts

* Revert "chore(release): publish" ([a015d1d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a015d1d92a4b1c0130c44fcef1c9ecdb157a0f07))
* don't force multiline flag for editor component patterns ([#3089](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3089)) ([c4cbae7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c4cbae77255d1f422fd62258a01007956d512392))





# [2.25.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.24.4...netlify-cms-core@2.25.0) (2020-04-20)


### Bug Fixes

* **types:** instead of the inferred {}, allow any kind of props ([#3638](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3638)) ([3f72f43](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3f72f438a1e2ad1111780208af69bf172becd277))


### Features

* add-download-button closes [#3429](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3429) ([#3609](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3609)) ([cf25260](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cf252605ad8fee6f3d307302dc50759813ee765c))





## [2.24.4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.24.3...netlify-cms-core@2.24.4) (2020-04-16)


### Bug Fixes

* redirect to default path after login success if url has prev error ([#3599](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3599)) ([bb0a7e9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/bb0a7e96d82d950735eafce3017460caf0fd6d0c))





## [2.24.3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.24.2...netlify-cms-core@2.24.3) (2020-04-14)


### Bug Fixes

* **type-defs:**  add string type to EditorComponentData id property ([#3602](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3602)) ([1a60e6d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1a60e6d7fde3c282df23487cd1f7479b0b848873))
* add missing generic type to registerPreviewTemplate ([#3597](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3597)) ([36ae69c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/36ae69c96eded5f4af4a9bd63e319f64b62b0e63))
* unify the title used in entry cards and workflow cards ([#3573](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3573)) ([#3575](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3575)) ([625a998](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/625a9980f1c113cb8e5159e42bfddfe94a0d6188))





## [2.24.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.24.1...netlify-cms-core@2.24.2) (2020-04-10)


### Bug Fixes

* enable merge option for yaml parser ([#3577](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3577)) ([b8eeab2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b8eeab2e35a51cb8128d2a0df23d8ecd489208cd))





## [2.24.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.24.0...netlify-cms-core@2.24.1) (2020-04-09)


### Bug Fixes

* allow unlimited alias count ([#3570](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3570)) ([bfb2e2b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/bfb2e2bc574d9b356aa14ffb3b6eb7eca285c73a))
* duplicate entry ([#3563](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3563)) ([1d88b15](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1d88b15de54d62d1d8d40a0391e9fc640af2ca97))
* pass prettyErrors to yaml when parsing config ([#3571](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3571)) ([0d59642](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0d59642e64e9341b3ac73ede4cfb0e4ba2980faa))
* use v1.1 schema only when parsing ([#3569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3569)) ([0761ffa](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0761ffa3f29c29a7b0c7cf56fdb38342bf25ff0e))





# [2.24.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.23.4...netlify-cms-core@2.24.0) (2020-04-07)


### Features

* **yaml:** support comments ([#3529](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3529)) ([4afbbdd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4afbbdd8a99241d239f28c5be544bb0ca77e345b))





## [2.23.4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.23.3...netlify-cms-core@2.23.4) (2020-04-06)


### Bug Fixes

* missing widgets ([#3541](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3541)) ([6933bf6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6933bf6ee1acbbefb2cc7840a8aef6accc2d455b))





## [2.23.3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.23.2...netlify-cms-core@2.23.3) (2020-04-01)


### Bug Fixes

* sanitize dots in path collection config ([#3518](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3518)) ([601175c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/601175c6a146139718b3aba430deafe899896cae))
* set default public_folder on files and fields ([#3519](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3519)) ([1a577b8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1a577b8e2740a5e12a4c7cb543ed4e78312fc4b3))
* stop collection view controls from overflowing ([#3521](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3521)) ([c2425b4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c2425b44e86b5addaa4876ecee0e33dfa387c6f5))





## [2.23.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.23.1...netlify-cms-core@2.23.2) (2020-04-01)


### Bug Fixes

* don't override empty public folder ([#3513](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3513)) ([a1bf86e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a1bf86e8566dfad123926339b16d9a16a4bfd77a))
* use resolveBackend instead of currentBackend ([#3514](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3514)) ([ea41b98](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ea41b98324c61891d639df93cbf26148d6a93db6))





## [2.23.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.23.0...netlify-cms-core@2.23.1) (2020-04-01)


### Bug Fixes

* media files when duplicating entry ([#3507](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3507)) ([9705295](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/970529570b11bbcf3fb65e91f2be09b699b20be7))





# [2.23.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.22.2...netlify-cms-core@2.23.0) (2020-03-30)


### Bug Fixes

* allow widgets to control value to be validated ([#3448](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3448)) ([ae1917c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ae1917c8181892a439d0828d98992788fb48d65c))
* don't use getAsset for draft entries ([#3403](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3403)) ([45a1654](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/45a1654404ef7bd24dd2f04a4b3f896d1eef0b7d))
* update error boundary about GitHub issue data ([#3471](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3471)) ([42d60a6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/42d60a644c58e01da72eb16c1cc20d93e0d70e13))


### Features

* add publish configuration option to collections ([#3467](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3467)) ([df33bc6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/df33bc64a996eedcb10835064a7cab8e7862e94d))





## [2.22.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.22.1...netlify-cms-core@2.22.2) (2020-03-20)


### Bug Fixes

* **core:** pass loadEntry to widgets as utility function and not redux action ([#3439](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3439)) ([6d87655](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6d8765521ca2f1b679b388b88b5101206c8f64f9))





## [2.22.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.22.0...netlify-cms-core@2.22.1) (2020-03-19)


### Bug Fixes

* **core:** custom widget validate bug in EditorControlPane ([#3435](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3435)) ([e81a35c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e81a35ccb8381c3132872f2d461134e1f4481080))
* call createDraftFromEntry after entry is loaded instead in Editor ([#3418](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3418)) ([2409323](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2409323dba1abe8a670d18453369fd75c6e240fb))





# [2.22.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.21.0...netlify-cms-core@2.22.0) (2020-03-12)


### Bug Fixes

* **type-defs:** signature for CMS.registerWidget ([#3386](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3386)) ([9c0f618](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9c0f61814859f06759798601b05d80745e4197be))
* cache assets using resolved path on error ([#3378](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3378)) ([f3fd43b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f3fd43b81928abaea99b50ee4223de3c0498cb71))
* ja locale labels ([#3367](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3367)) ([50837b0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/50837b0068ac8972ce16cbf5f238aa5a2c5bd6e9))
* show better error for missing widgets ([#3377](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3377)) ([ff3b62d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ff3b62d12fc853fb3b712b7b33bf7064a6579a04))


### Features

* add media lib virtualization ([#3381](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3381)) ([92e7601](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/92e76011e7a9e8b5370088b0a2c065df66b5f7fb))
* support filename and extension vars in summary ([#3375](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3375)) ([12444ca](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12444ca761d5cd40d766847f117e55b0e0ca6e9e))





# [2.21.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.20.1...netlify-cms-core@2.21.0) (2020-03-03)


### Bug Fixes

* consider variable types when traversing collection fields ([#3347](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3347)) ([961cde4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/961cde4ea523027a1367bbdb84adbc2843a79b57))
* ensure draft changes ([#3306](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3306)) ([cf81f58](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cf81f587cf517b2906e261e89090de984aad3ce3))


### Features

* populate new entry from URL params ([#3343](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3343)) ([e0b1246](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e0b124681093c6f1dff9b9ec0ffab835716e66b5))





## [2.20.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.20.0...netlify-cms-core@2.20.1) (2020-02-27)


### Bug Fixes

* preserve unknown fields value ([#3314](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3314)) ([908c42f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/908c42fb588ce87f4e197df65db2d238f34837f4))
* **core:** improve editor buttons for smaller screens ([#3327](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3327)) ([53365b7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/53365b73701c872948a1e65da00a655e0718e8cb))





# [2.20.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.19.1...netlify-cms-core@2.20.0) (2020-02-25)


### Features

* sanitize media filenames according to global slug setting ([#3315](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3315)) ([8874769](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8874769b317e6e364c881039c0c9308826f49cff))





## [2.19.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.19.0...netlify-cms-core@2.19.1) (2020-02-25)


### Bug Fixes

* **backend-github:** improve workflow migration edge cases/messaging ([#3319](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3319)) ([684b79e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/684b79e43bebb63ce1e844eae5c8c0e76087687b))





# [2.19.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.18.4...netlify-cms-core@2.19.0) (2020-02-22)


### Features

* Add 'hero' as inferable image field ([#3294](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3294)) ([971926c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/971926c36941694acdc37649494f1f62f3f5f40e))





## [2.18.4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.18.3...netlify-cms-core@2.18.4) (2020-02-14)


### Bug Fixes

* **core:** report config error when external media lib is missing ([#3255](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3255)) ([1d63038](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1d63038e78a6db1e7a061b5ba447f951d892595a))
* dispatch QUERY_FAILURE on query failure ([#3243](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3243)) ([2447f9c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2447f9c311db3c5db35ce6501c0380d304709d50))





## [2.18.3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.18.2...netlify-cms-core@2.18.3) (2020-02-13)


### Bug Fixes

* change getAsset to not return a promise ([#3232](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3232)) ([ab685e8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ab685e85943d1ac48142f157683bc2126fd6af16))





## [2.18.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.18.1...netlify-cms-core@2.18.2) (2020-02-12)


### Bug Fixes

* handle missing inferred title field ([#3239](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3239)) ([ca8cf71](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ca8cf71ab0d479547c649fb1fce8e72db6207c27))





## [2.18.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.18.0...netlify-cms-core@2.18.1) (2020-02-11)


### Bug Fixes

* **core:** use correct name for edit route param ([#3236](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3236)) ([cfd2fed](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cfd2fed494dc707e03ade086009ebfdd27578477))





# [2.18.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.17.0...netlify-cms-core@2.18.0) (2020-02-10)


### Features

* **proxy-server:** add local fs middleware and make it the default ([#3217](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3217)) ([31dbd72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/31dbd72273b723bb6bbb551641a6e4bcc1f0314b))
* field based media/public folders ([#3208](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3208)) ([97bc0c8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/97bc0c8dc489e736f89d748ba832d78400fe4332))


### Reverts

* Revert "chore(release): publish" ([a015d1d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a015d1d92a4b1c0130c44fcef1c9ecdb157a0f07))





# [2.17.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.16.0...netlify-cms-core@2.17.0) (2020-02-06)


### Bug Fixes

* **core:** strip closing separators in yaml files ([#3198](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3198)) ([60ecc72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/60ecc72dfab660eea795fb1307df8596d65cd78b))
* **locale:** remove hard coded strings ([#3193](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3193)) ([fc91bf8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/fc91bf8781e65ce1dc946363dbb10419a145c66b))
* load missing assets when retrieving backup ([#3192](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3192)) ([7d792f3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7d792f3005b1092c393c39ced90e2408fb43236b))
* media library on reload ([#3174](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3174)) ([4f55442](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4f5544287fbd13be03794ec15bcfe992588290ed))


### Features

* **core:** auto detect proxy server on load ([#3195](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3195)) ([614f1ae](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/614f1aea63de672a89dc55d485ad0302bc1f1bf2))
* add preUnpublish, postUnpublish events ([#3196](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3196)) ([18e284e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18e284ece83fb6ae07a953dbdefe347bc48d4acc))





# [2.16.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.15.5...netlify-cms-core@2.16.0) (2020-02-01)


### Features

* add prePublish,postPublish events ([#3172](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3172)) ([0d7e36b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0d7e36ba7952b1353b5a5bc4417994d45596a9a1))





## [2.15.5](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.15.4...netlify-cms-core@2.15.5) (2020-01-30)


### Bug Fixes

* media file path ([#3166](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3166)) ([d1179e3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d1179e3999cba5a022981042262c8e44e26c53d1))





## [2.15.4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.15.3...netlify-cms-core@2.15.4) (2020-01-29)


### Bug Fixes

* allow absolute paths for collection media folder ([#3160](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3160)) ([a215cfb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a215cfbe3aa875fb932878039a5efbde6d97b538))
* don't show duplicate entry when create is disabled ([#3162](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3162)) ([06c045e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/06c045e4e610d0578619ad0c7f787e41de769980))





## [2.15.3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.15.2...netlify-cms-core@2.15.3) (2020-01-22)

**Note:** Version bump only for package netlify-cms-core





## [2.15.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.15.1...netlify-cms-core@2.15.2) (2020-01-15)


### Reverts

* don't force multiline flag for editor component patterns ([#3089](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3089)) ([c4cbae7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c4cbae77255d1f422fd62258a01007956d512392))





## [2.15.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.15.0...netlify-cms-core@2.15.1) (2020-01-14)

**Note:** Version bump only for package netlify-cms-core





# [2.15.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.14.1...netlify-cms-core@2.15.0) (2020-01-14)


### Bug Fixes

* **core:** force multiline flag for editor component patterns ([#3082](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3082)) ([476f450](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/476f45096efa1723936a73f2e2e04d5c7ccd293f))


### Features

* support per collection public_folder ([#3069](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3069)) ([0a50efd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0a50efda8e5a9e5cc99291890e3eab2307266c56))





## [2.14.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.14.0...netlify-cms-core@2.14.1) (2020-01-09)


### Bug Fixes

* don't wait for external media library to load ([#3050](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3050)) ([5bd7240](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5bd724026c8ebc08c56514f2c983d49c25c914ee))





# [2.14.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.14.0-beta.1...netlify-cms-core@2.14.0) (2020-01-07)


### Bug Fixes

* always ensure collection exists before routing ([#2992](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2992)) ([982fd7b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/982fd7b0f88f851d4e9bb33c8430313c2e816f43))
* cleanup nested widget validation ([#2991](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2991)) ([e4ba4d9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e4ba4d9d749c864e594c10e0bb31b0b8c4e6e60b))
* duplicate and new entry action ([#3003](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3003)) ([9e7aa0c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9e7aa0c500f2bd394ca711846ec88c2b4fbf7ec5))
* rebase open authoring branches ([#2975](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2975)) ([8c175f6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8c175f6132fa18a13763cc563f7d3201c1e3580e))


### Features

* **backend-git-gateway:** handle identity disabled error message ([#3002](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/3002)) ([b5ffccd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b5ffccdac506db416c09aaebb38611783487c52a))





# [2.14.0-beta.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.14.0-beta.0...netlify-cms-core@2.14.0-beta.1) (2019-12-19)


### Bug Fixes

* select widget dropdown options ([#2981](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2981)) ([9173d8c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9173d8c97e27a3742a25c36cc7cb11202c861385))





# [2.14.0-beta.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0...netlify-cms-core@2.14.0-beta.0) (2019-12-18)


### Features

* bundle assets with content ([#2958](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2958)) ([2b41d8a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2b41d8a838a9c8a6b21cde2ddd16b9288334e298))





# [2.13.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.10...netlify-cms-core@2.13.0) (2019-12-18)


### Bug Fixes

* don't show progress when loading preview status ([#2974](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2974)) ([af61245](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/af6124536013e95b417501ef17f1144baffada72))





# [2.13.0-beta.10](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.9...netlify-cms-core@2.13.0-beta.10) (2019-12-16)


### Features

* Code Widget + Markdown Widget Internal Overhaul ([#2828](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2828)) ([18c579d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18c579d0e9f0ff71ed8c52f5c66f2309259af054))





# [2.13.0-beta.9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.8...netlify-cms-core@2.13.0-beta.9) (2019-12-11)


### Features

* duplicate entry ([#2956](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2956)) ([d180bff](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d180bffb44432a82f2b4e5a08df5693b30268fee))





# [2.13.0-beta.8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.7...netlify-cms-core@2.13.0-beta.8) (2019-12-02)


### Bug Fixes

* .d.ts definitions for core and app ([#2929](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2929)) ([7391061](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7391061b3b8b1971b994f497a6df29b7d5c3da74))
* keep editor slug path ([#2934](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2934)) ([3c4865f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3c4865f2a76e6b0f156ab801081251eb620495b2))
* load unpublished entries ([#2927](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2927)) ([caaa8b6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/caaa8b6db408623fd6001b9a8bad5d4711afbc76))
* unpublish published entry ([#2931](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2931)) ([45a6ee9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/45a6ee92cc9322c57a3cd996b33c07d26c2d645e))
* **core:** use UTC date methods for slug formatting ([#2944](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2944)) ([d0b32a7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d0b32a7a0af62c08433f7d3ce0828214714ce28e))


### Features

* content in sub folders ([#2897](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2897)) ([afcfe5b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/afcfe5b6d5f32669e9061ec596bd35ad545d61a3))





# [2.13.0-beta.7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.6...netlify-cms-core@2.13.0-beta.7) (2019-11-26)


### Bug Fixes

* emotion use ref prop ([#2905](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2905)) ([9ddfa48](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9ddfa48512e54c77fc8e9a0f2eba4f0abf7c9029))
* **backend-github:** prepend collection name ([#2878](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2878)) ([465f463](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/465f4639597f258d5aa2c1b65e9d2c16023ee7ae))
* **deps:** update dependency react-is to v16.12.0 ([#2912](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2912)) ([695b0e0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/695b0e03805e7e1610787ec5f093499681bd3568))


### Features

* workflow unpublished entry ([#2914](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2914)) ([41bb9aa](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/41bb9aac0dd6fd9f8ff157bb0b29c85aa87fe04d))





# [2.13.0-beta.6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.5...netlify-cms-core@2.13.0-beta.6) (2019-11-18)


### Bug Fixes

* **media-libs:** accept string or string array for insertMedia action ([#2857](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2857)) ([f5c8ff3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f5c8ff31f121e550f81b2472f2e3f0c8d76aab1b))
* **workflow:** label file collection entries in Workflow ([#2566](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2566)) ([542a7ac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/542a7acfe60719f30bbb1ec8da37f6a498194400))


### Features

* add translation support ([#2870](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2870)) ([096b067](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/096b067d4542c723630ded631fc9a4ba950732f3)), closes [#2877](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2877)
* commit media with post ([#2851](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2851)) ([6515dee](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6515dee8715d8571ea19484a7dfab7cfd0cc40be))





# [2.13.0-beta.5](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.4...netlify-cms-core@2.13.0-beta.5) (2019-11-07)


### Bug Fixes

* **backend-test-repo:** show notice when test repo is in use ([#2678](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2678)) ([c1c9587](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c1c95874f41bd2b435c39d3dea263c77eaa601eb))
* **deps:** update dependency react-polyglot to ^0.6.0 ([#2752](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2752)) ([ab5860f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ab5860f58ea15b69e860164986d7e24867d01954))
* change default open authoring scope, make it configurable ([#2821](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2821)) ([002cdd7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/002cdd77a856bde3672e75dde6d3a2b246e1035f))
* hide collection item overflow on hover ([#2706](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2706)) ([c54f896](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c54f896e3965e7d737cfca24fda283ab38d07982))


### Features

* enable specifying custom open authoring commit message ([#2810](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2810)) ([2841ff9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2841ff9ffe58afcf4dba45514a84a262ad370f1d))





# [2.13.0-beta.4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.3...netlify-cms-core@2.13.0-beta.4) (2019-09-26)


### Bug Fixes

* **core:** list widget pattern validation ([#2599](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2599)) ([6765bbd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6765bbd))
* **media-library:** automatically select uploaded image ([#2569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2569)) ([9f00310](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9f00310))
* prevent deletion of file collection entries by default ([#2627](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2627)) ([8bdfea4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/8bdfea4))





# [2.13.0-beta.3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.2...netlify-cms-core@2.13.0-beta.3) (2019-09-04)


### Bug Fixes

* **core:** don't pass boolean value to string prop, use null instead ([#2609](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2609)) ([ce95a77](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ce95a77))
* **core:** don't pass ref to react-polyglot 'translate' function component ([#2607](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2607)) ([5b64e25](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5b64e25))
* **github-graphql:** use getMediaDisplayURL to load media with auth header ([#2652](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2652)) ([e674e43](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e674e43))
* **media-library:** no render of non-viewable files ([#2546](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2546)) ([4c5fe6a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4c5fe6a))


### Features

* **routing:** support direct linking to entries ([#2556](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2556)) ([083a336](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/083a336))





# [2.13.0-beta.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.1...netlify-cms-core@2.13.0-beta.2) (2019-08-24)

**Note:** Version bump only for package netlify-cms-core





# [2.13.0-beta.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.13.0-beta.0...netlify-cms-core@2.13.0-beta.1) (2019-08-24)

**Note:** Version bump only for package netlify-cms-core





# [2.13.0-beta.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.12.2...netlify-cms-core@2.13.0-beta.0) (2019-07-24)


### Features

* **backend-github:** Open Authoring ([#2430](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2430)) ([edf0a3a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/edf0a3a))





## [2.12.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.12.1...netlify-cms-core@2.12.2) (2019-07-24)


### Bug Fixes

* **core:** fix broken search ([#2488](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2488)) ([326ed4d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/326ed4d))





## [2.12.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.12.0...netlify-cms-core@2.12.1) (2019-06-28)


### Bug Fixes

* **core:** load more entries until viewport is filled ([#2415](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2415)) ([a02496b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a02496b))





# [2.12.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.11.1...netlify-cms-core@2.12.0) (2019-06-26)


### Bug Fixes

* **core:** backend file system create entry ([#2401](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2401)) ([556c102](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/556c102))
* **widget-list:** validate string values in list widget ([#2385](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2385)) ([814aa50](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/814aa50))


### Features

* **widget-relation:** support nested field references in relation widget ([#2391](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2391)) ([d6964b5](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d6964b5))





## [2.11.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.11.1-beta.2...netlify-cms-core@2.11.1) (2019-06-14)

**Note:** Version bump only for package netlify-cms-core





## [2.11.1-beta.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.11.1-beta.1...netlify-cms-core@2.11.1-beta.2) (2019-06-14)


### Bug Fixes

* **core:** list widget default values ([#2374](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2374)) ([1806a2f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1806a2f))





## [2.11.1-beta.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.11.1-beta.0...netlify-cms-core@2.11.1-beta.1) (2019-05-15)

**Note:** Version bump only for package netlify-cms-core





## [2.11.1-beta.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.11.0...netlify-cms-core@2.11.1-beta.0) (2019-04-10)


### Bug Fixes

* **core:** ensure against slug overwrite ([#2139](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2139)) ([0ce995d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0ce995d))





# [2.11.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.11.0-beta.2...netlify-cms-core@2.11.0) (2019-04-10)

**Note:** Version bump only for package netlify-cms-core





# [2.11.0-beta.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.11.0-beta.1...netlify-cms-core@2.11.0-beta.2) (2019-04-05)


### Bug Fixes

* **core:** correctly delete backups for new entries ([#2265](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2265)) ([a6c51fe](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/a6c51fe))





# [2.11.0-beta.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.11.0-beta.0...netlify-cms-core@2.11.0-beta.1) (2019-04-02)


### Bug Fixes

* redirect when a collection doesn't exist ([#2208](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2208)) ([9e08b65](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9e08b65))





# [2.11.0-beta.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.10.1...netlify-cms-core@2.11.0-beta.0) (2019-03-29)


### Features

* **core:** allow custom summary on entry cards ([#2140](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2140)) ([573ad88](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/573ad88))





## [2.10.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.10.1-beta.2...netlify-cms-core@2.10.1) (2019-03-29)

**Note:** Version bump only for package netlify-cms-core





## [2.10.1-beta.2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.10.1-beta.1...netlify-cms-core@2.10.1-beta.2) (2019-03-28)


### Bug Fixes

* broken preview ([#2245](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2245)) ([4db497b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/4db497b))





## [2.10.1-beta.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.10.1-beta.0...netlify-cms-core@2.10.1-beta.1) (2019-03-26)


### Bug Fixes

* export on netlify-cms and maps on esm ([#2244](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2244)) ([6ffd13b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6ffd13b))





## [2.10.1-beta.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.10.0...netlify-cms-core@2.10.1-beta.0) (2019-03-25)


### Bug Fixes

* update peer dep versions ([#2234](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2234)) ([7987091](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7987091))
* **deps:** update dependency react-is to v16.8.5 ([#2232](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2232)) ([6e2d18f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/6e2d18f))





# [2.10.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.9.1-beta.0...netlify-cms-core@2.10.0) (2019-03-22)


### Features

* add ES module builds ([#2215](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2215)) ([d142b32](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d142b32))





## [2.9.1-beta.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.9.0...netlify-cms-core@2.9.1-beta.0) (2019-03-22)


### Bug Fixes

* **editorial-workflow:** fix LM pointers changing to binary files ([#2228](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2228)) ([d39a361](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d39a361))





# [2.9.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.9.0-beta.0...netlify-cms-core@2.9.0) (2019-03-22)

**Note:** Version bump only for package netlify-cms-core





# [2.9.0-beta.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.8.1-beta.0...netlify-cms-core@2.9.0-beta.0) (2019-03-21)


### Bug Fixes

* **deps:** update dependency react-polyglot to ^0.4.0 ([#2170](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2170)) ([d5248c8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d5248c8))
* fix umd builds ([#2214](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2214)) ([e04f6be](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/e04f6be))


### Features

* provide usable UMD builds for all packages ([#2141](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2141)) ([82cc794](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/82cc794))





## [2.8.1-beta.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.8.1-alpha.0...netlify-cms-core@2.8.1-beta.0) (2019-03-15)


### Bug Fixes

* **deps:** update dependency react-scroll-sync to ^0.7.0 ([#2171](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2171)) ([12cc5a9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12cc5a9))
* **deps:** update dependency react-sortable-hoc to v1 ([#2198](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2198)) ([b5180e9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b5180e9))


### Features

* upgrade to Emotion 10 ([#2166](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2166)) ([ccef446](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ccef446))





## [2.8.1-alpha.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.8.0...netlify-cms-core@2.8.1-alpha.0) (2019-03-14)

**Note:** Version bump only for package netlify-cms-core





# [2.8.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.7.0...netlify-cms-core@2.8.0) (2019-03-08)


### Bug Fixes

* **config:** strip leading slashes from collection location config ([#2131](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2131)) ([efa650c](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/efa650c))
* **core:** allow updates through error boundary ([#2136](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2136)) ([3d98b72](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/3d98b72))
* **core:** number type slug template ([#2119](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2119)) ([7577443](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/7577443))


### Features

* **core:** recover entry after unexpected quit ([#2129](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2129)) ([686504a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/686504a))





# [2.7.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.6.0...netlify-cms-core@2.7.0) (2019-02-26)


### Bug Fixes

* **widget-relation:** fix initial relation widget preview ([#2090](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2090)) ([aff9c1a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/aff9c1a))


### Features

* **netlify-cms-widget-relation:** use react-select and add support for multiple entries ([#1936](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1936)) ([518f6fb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/518f6fb))





# [2.6.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.5.1...netlify-cms-core@2.6.0) (2019-02-12)


### Features

* **core:** allow field name to override slug placeholders ([#2087](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2087)) ([ff8dfac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ff8dfac))





## [2.5.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.5.0...netlify-cms-core@2.5.1) (2019-02-09)

**Note:** Version bump only for package netlify-cms-core





# [2.5.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.4.1...netlify-cms-core@2.5.0) (2019-02-08)


### Bug Fixes

* **netlify-cms-core:** allow arrays for frontmatter_delimiter in config ([#1997](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1997)) ([ebba686](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/ebba686))
* **netlify-cms-core:** fix fields metadata for objects and lists ([#2011](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2011)) ([2d1d1c1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2d1d1c1))
* **netlify-cms-core:** relation widget value swap ([#2018](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2018)) ([11305d3](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/11305d3))
* **netlify-cms-core:** validate nested fields ([#1873](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1873)) ([627e600](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/627e600))


### Features

* **config:** allow config.yml file load to be skipped ([#2053](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2053)) ([14f94a0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/14f94a0))
* **netlify-cms-core:** expose loadEntry action to Widgets ([#2010](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2010)) ([5d8aef1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/5d8aef1))
* **netlify-cms-widget-map:** add map widget ([#2051](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2051)) ([18f34d2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/18f34d2))
* **widget-number:** add range validation ([#2049](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2049)) ([dc44cac](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/dc44cac))
* **workflow:** add deploy preview links ([#2028](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/2028)) ([15d221d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/15d221d))


### Performance Improvements

* **netlify-cms-core:** add basic route code-splitting ([#1889](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1889)) ([9aa5645](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9aa5645))





## [2.4.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.4.0...netlify-cms-core@2.4.1) (2019-01-10)


### Bug Fixes

* **netlify-cms-core:** files collection blank label ([#1987](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1987)) ([f2e4800](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/f2e4800))





# [2.4.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.3.1...netlify-cms-core@2.4.0) (2018-12-27)


### Bug Fixes

* **netlify-cms-core:** avoid leading replacement char in slug ([#1965](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1965)) ([79c0445](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/79c0445))
* **netlify-cms-core:** avoid partially loaded collection list ([#1964](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1964)) ([cedcbf8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/cedcbf8))
* **netlify-cms-core:** fix collection entries loaded check ([#1881](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1881)) ([b374ffe](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b374ffe))
* **netlify-cms-core:** workflow hide delete publish entry button ([#1971](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1971)) ([44fb2fb](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/44fb2fb))


### Features

* **editor:** display optional status in widget labels ([#1955](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1955)) ([44b7cdf](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/44b7cdf))





## [2.3.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.3.0...netlify-cms-core@2.3.1) (2018-12-11)


### Bug Fixes

* **netlify-cms-core:** support translation in error message ([#1935](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1935)) ([0f1ebd1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0f1ebd1))





# [2.3.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.2.1...netlify-cms-core@2.3.0) (2018-12-04)


### Bug Fixes

* **netlify-cms-core:** duplicate key warning ([#1930](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1930)) ([9662eb2](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/9662eb2))


### Features

* **netlify-cms-widget-select:** add support for multiple selection ([#1901](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1901)) ([88bf287](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/88bf287))
* add cloudinary support ([#1932](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1932)) ([1fc2f50](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/1fc2f50))





## [2.2.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.2.0...netlify-cms-core@2.2.1) (2018-11-29)


### Bug Fixes

* correct validation pattern error message ([#1879](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1879)) ([2a63940](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2a63940))
* fix entry saved message ([#1887](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1887)) ([c4e474b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c4e474b))
* MediaLibraryHeader CloseButton style ([#1883](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1883)) ([034c29a](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/034c29a))
* **a11y:** correct label "for" references to fields ([#1904](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1904)) ([955f94f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/955f94f))
* **backend:** use singular label in custom commit message ([#1917](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1917)) ([2c5827b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/2c5827b))
* **config:** remove identifier field validation ([#1882](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1882)) ([fe6af19](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/fe6af19))
* **netlify-cms-core:** fix identifier field validation ([#1907](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1907)) ([d5f4c99](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d5f4c99))
* **netlify-cms-core:** fix prop-types warnings ([#1906](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1906)) ([751ec09](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/751ec09))
* **netlify-cms-core:** remove double focusable elements on profile menu button ([#1900](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1900)) ([888ae6b](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/888ae6b))





# [2.2.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.1.1...netlify-cms-core@2.2.0) (2018-11-12)


### Bug Fixes

* **config:** allow setting publish_mode to 'simple' ([#1827](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1827)) ([288359d](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/288359d))
* **i18n:** fix missing widget placeholder ([#1861](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1861)) ([b1a7e00](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/b1a7e00))
* **widget-date:** fix default value for nested date widget ([#1859](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1859)) ([d8f8887](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d8f8887))
* **widgets:** fix list object field default values ([#1826](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1826)) ([c765793](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c765793))
* fix App configError method ([#1864](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1864)) ([79205f7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/79205f7))


### Features

* **config:** add support for setting custom identifier field ([#1543](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1543)) ([12418dd](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/12418dd))
* allow custom logo on auth page ([#1818](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1818)) ([c6ae1e8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/c6ae1e8))





<a name="2.1.1"></a>
## [2.1.1](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.1.0...netlify-cms-core@2.1.1) (2018-10-09)


### Bug Fixes

* **config:** stop throwing on config.yml 404, fix manual init ([#1801](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1801)) ([d06c663](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/d06c663))




<a name="2.1.0"></a>
# [2.1.0](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.0.9...netlify-cms-core@2.1.0) (2018-09-06)


### Features

* **media:** add external media library support, Uploadcare integration ([#1602](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1602)) ([0596904](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0596904))




<a name="2.0.9"></a>
## [2.0.9](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.0.8...netlify-cms-core@2.0.9) (2018-08-27)




**Note:** Version bump only for package netlify-cms-core

<a name="2.0.8"></a>
## [2.0.8](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.0.7...netlify-cms-core@2.0.8) (2018-08-24)


### Bug Fixes

* make media button consistent with links ([#1621](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1621)) ([412d1e6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/412d1e6))
* **gitlab:** fetch media library images through API ([#1433](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1433)) ([83d2adc](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/83d2adc))
* **list-widget:** fix single field usage in list widget ([#1395](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1395)) ([06d3650](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/06d3650))




<a name="2.0.7"></a>
## [2.0.7](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.0.6...netlify-cms-core@2.0.7) (2018-08-07)


### Bug Fixes

* **relation:** fix relation widget selection bug ([#1572](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1572)) ([77fbc04](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/77fbc04))




<a name="2.0.6"></a>
## [2.0.6](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.0.5...netlify-cms-core@2.0.6) (2018-08-01)


### Bug Fixes

* **workflow:** enable workflow per method ([#1569](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1569)) ([90b8156](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/90b8156))




<a name="2.0.5"></a>
## [2.0.5](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.0.4...netlify-cms-core@2.0.5) (2018-08-01)


### Bug Fixes

* **workflow:** fix status not set on new workflow entries ([#1558](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1558)) ([0aa085f](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/0aa085f))
* only trim periods from file extensions ([#1554](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/issues/1554)) ([95c744e](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/commit/95c744e))




<a name="2.0.4"></a>
## [2.0.4](https://github.com/netlify/netlify-cms/tree/master/packages/netlify-cms-core/compare/netlify-cms-core@2.0.3...netlify-cms-core@2.0.4) (2018-07-28)




**Note:** Version bump only for package netlify-cms-core

<a name="2.0.3"></a>
## [2.0.3](https://github.com/netlify/netlify-cms/compare/netlify-cms-core@2.0.2...netlify-cms-core@2.0.3) (2018-07-27)


### Bug Fixes

* log accurate version by distribution ([#1531](https://github.com/netlify/netlify-cms/issues/1531)) ([95a76ad](https://github.com/netlify/netlify-cms/commit/95a76ad))




<a name="2.0.2"></a>
## 2.0.2 (2018-07-27)


### Bug Fixes

* bug fixes from linters ([#1524](https://github.com/netlify/netlify-cms/issues/1524)) ([6632e5d](https://github.com/netlify/netlify-cms/commit/6632e5d))
* fix version console log ([#1528](https://github.com/netlify/netlify-cms/issues/1528)) ([e82289b](https://github.com/netlify/netlify-cms/commit/e82289b))



<a name="2.0.1"></a>
## 2.0.1 (2018-07-26)



<a name="2.0.0"></a>
# 2.0.0 (2018-07-26)




**Note:** Version bump only for package netlify-cms-core
