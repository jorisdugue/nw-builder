# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/) using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

Since `v4.6.0`, we have switched to automated releases and this file does not need to be manually updated.

## [5.0.0](https://github.com/jorisdugue/nw-builder/compare/v4.6.0...v5.0.0) (2024-02-12)


### ⚠ BREAKING CHANGES

* refactor run and bld mode ([#661](https://github.com/jorisdugue/nw-builder/issues/661))

### Features

* add `get` mode ([d34580e](https://github.com/jorisdugue/nw-builder/commit/d34580e5d28fd6355c582f1ee36552eef99ace78))
* add `glob` flag ([#829](https://github.com/jorisdugue/nw-builder/issues/829)) ([d55c1a3](https://github.com/jorisdugue/nw-builder/commit/d55c1a37ba3b551e0996f5f27087b2eeee8848d8))
* add macos arm support ([#783](https://github.com/jorisdugue/nw-builder/issues/783)) ([de90708](https://github.com/jorisdugue/nw-builder/commit/de9070805ae98d82ef5bb184b110f5faa36e06bb))
* **api:** match all options in the module, cli and `package.json` ([#586](https://github.com/jorisdugue/nw-builder/issues/586)) ([f5daaab](https://github.com/jorisdugue/nw-builder/commit/f5daaabef4446842f714748a205788bd1269d039))
* **api:** optional zip file merging ([#567](https://github.com/jorisdugue/nw-builder/issues/567)) ([8b0e72d](https://github.com/jorisdugue/nw-builder/commit/8b0e72df53904e2e98669bea353b306aa1ef5c81))
* **args:** improve api dx ([#488](https://github.com/jorisdugue/nw-builder/issues/488)) ([b54e81d](https://github.com/jorisdugue/nw-builder/commit/b54e81d63dfabe49c275a0898b33e895c938cdb7))
* **build:** add managed manifest ([#965](https://github.com/jorisdugue/nw-builder/issues/965)) ([efb17e9](https://github.com/jorisdugue/nw-builder/commit/efb17e9af74a655494f3f717fe98fdbd9c9b8ec7))
* **build:** node native addon support via gyp ([#964](https://github.com/jorisdugue/nw-builder/issues/964)) ([b55f200](https://github.com/jorisdugue/nw-builder/commit/b55f200550ad0fe63682f8c4debe01b87e3d2203))
* compress to `zip`, `tar` and `tgz` formats ([#890](https://github.com/jorisdugue/nw-builder/issues/890)) ([b825fed](https://github.com/jorisdugue/nw-builder/commit/b825fed7fd122a63cb3b53060c29abfc170d1470))
* **docs:** add repro link to issue template ([3dc840c](https://github.com/jorisdugue/nw-builder/commit/3dc840c5adca3ae0b7c222f05945be9a68a9a8c8))
* **get:** align cache impl with `nwjs/npm-installer` ([#967](https://github.com/jorisdugue/nw-builder/issues/967)) ([efa46b8](https://github.com/jorisdugue/nw-builder/commit/efa46b8c681948986548cd0805823eeb2a3c8e00))
* **get:** set `cacheDir` on another volume ([#1023](https://github.com/jorisdugue/nw-builder/issues/1023)) ([7c0f711](https://github.com/jorisdugue/nw-builder/commit/7c0f711d407c4f992e7897e9d590f03d3105db4e)), closes [#1017](https://github.com/jorisdugue/nw-builder/issues/1017)
* integrate ffmpeg ([#802](https://github.com/jorisdugue/nw-builder/issues/802)) ([3136569](https://github.com/jorisdugue/nw-builder/commit/31365695c04aee2a4704f289b47e041a4d7ea38e))
* refactor run and bld mode ([#661](https://github.com/jorisdugue/nw-builder/issues/661)) ([cac5a13](https://github.com/jorisdugue/nw-builder/commit/cac5a131e23a514477b3b77b5fe8721ee2b4e3a7))
* specify log level via `options.logLevel` ([#892](https://github.com/jorisdugue/nw-builder/issues/892)) ([078a82e](https://github.com/jorisdugue/nw-builder/commit/078a82ed4aaf46c4e26fa72a323e1795a70a947a))
* update `MacOS` metadata ([#894](https://github.com/jorisdugue/nw-builder/issues/894)) ([6087691](https://github.com/jorisdugue/nw-builder/commit/6087691c51bbf0946a0c99d01901773acbda0189))


### Bug Fixes

* `MacOS` icon and unofficial `MacOS` arm build ([#896](https://github.com/jorisdugue/nw-builder/issues/896)) ([eba33cc](https://github.com/jorisdugue/nw-builder/commit/eba33cc6dc7887038159de72e8d2e0718e130d64))
* `osx` builds to allow nwjs launch ([#717](https://github.com/jorisdugue/nw-builder/issues/717)) ([aa38a56](https://github.com/jorisdugue/nw-builder/commit/aa38a56817b08cec6e4e7ffba47783ee2981e3b1))
* 716: warn about loss of file permissions ([8793d4b](https://github.com/jorisdugue/nw-builder/commit/8793d4bf06288199fcaff340fda43c1e2fbcacbc))
* 753: prevent duplicate globing ([07901c9](https://github.com/jorisdugue/nw-builder/commit/07901c9e3930481ead0977b9be731765df28c087))
* 760: error with version=latest ([33ef184](https://github.com/jorisdugue/nw-builder/commit/33ef184467f78fed94541e876da042b4ed99d443))
* add back `nwbuild` function ([efd020f](https://github.com/jorisdugue/nw-builder/commit/efd020fee10d20add16b9cc038abdf2178a75ff4))
* add back globing ([#749](https://github.com/jorisdugue/nw-builder/issues/749)) ([6edff46](https://github.com/jorisdugue/nw-builder/commit/6edff465de473bb6b3d5edd33495f2e8461e1b38))
* allow list specific mirrors ([bf7a53d](https://github.com/jorisdugue/nw-builder/commit/bf7a53d69bfed59cc5f0833c50e91fca067b9a71)), closes [#808](https://github.com/jorisdugue/nw-builder/issues/808)
* await platform-specific config ([#794](https://github.com/jorisdugue/nw-builder/issues/794)) ([082a436](https://github.com/jorisdugue/nw-builder/commit/082a4361e208f2bcc9b9fbffe8f11efff29660c1))
* **build:** do not copy first package.json encountered to root of options.outDir when options.glob is enabled ([dac3b4a](https://github.com/jorisdugue/nw-builder/commit/dac3b4a47d697b8019e0053dea5cc35a09d73135))
* change manifest cache impl ([#888](https://github.com/jorisdugue/nw-builder/issues/888)) ([3bb9489](https://github.com/jorisdugue/nw-builder/commit/3bb9489bddd8a6bb7f4e70210e109f425b23162a))
* check for first instance of `package.json` ([#644](https://github.com/jorisdugue/nw-builder/issues/644)) ([52fa1e6](https://github.com/jorisdugue/nw-builder/commit/52fa1e6e875d8571e6b13330c1137d340448f6d1))
* **chore:** resolve problem of missing folder when unzip ([2b1bc24](https://github.com/jorisdugue/nw-builder/commit/2b1bc24ece83bf7570c656837409de059d2d738d))
* **cicd:** rename branch to `main` ([d06e1e8](https://github.com/jorisdugue/nw-builder/commit/d06e1e8a8544ecc646633f60941d17e9ef8a3203))
* **ci:** update dependabot directory ([23b9b5f](https://github.com/jorisdugue/nw-builder/commit/23b9b5fb8dee0009329bd7f9b79c9f5cec64d432))
* **ci:** update import file extensions ([93cc727](https://github.com/jorisdugue/nw-builder/commit/93cc72751cec585fae42bc0dcf722254f716bdc3))
* cjs support ([#700](https://github.com/jorisdugue/nw-builder/issues/700)) ([2c0026f](https://github.com/jorisdugue/nw-builder/commit/2c0026f2b52746c563a33f910d4fd8a02296e8eb))
* cjs support ([#713](https://github.com/jorisdugue/nw-builder/issues/713)) ([2ea5364](https://github.com/jorisdugue/nw-builder/commit/2ea53641f43803d06ad271856d75a64672ffa567))
* cli `package.json` options ([#684](https://github.com/jorisdugue/nw-builder/issues/684)) ([dfae361](https://github.com/jorisdugue/nw-builder/commit/dfae36194ca123e863c1eae02c86e918b8254602))
* **cli:** add missing options ([#575](https://github.com/jorisdugue/nw-builder/issues/575)) ([79756ed](https://github.com/jorisdugue/nw-builder/commit/79756ed0b2733653e94492303427d95e14e660cd))
* **cli:** add support for comma seperated values without spaces ([306de31](https://github.com/jorisdugue/nw-builder/commit/306de310e56f73731d05038a34943fc74688ac57))
* **cli:** convert `srcDir` array to string ([1a699af](https://github.com/jorisdugue/nw-builder/commit/1a699af300782e0847333bb7ad945dbde8940350))
* **cli:** nwbuild import ([27b0164](https://github.com/jorisdugue/nw-builder/commit/27b01644597647aec6561bd5cd7122d9c368f564))
* **cli:** support multiple file paths ([#609](https://github.com/jorisdugue/nw-builder/issues/609)) ([9469f97](https://github.com/jorisdugue/nw-builder/commit/9469f97a33b32a7247fa42b0eab851ac4d5655c0))
* **cli:** use asterisk import to import `yargs/helpers` ([#998](https://github.com/jorisdugue/nw-builder/issues/998)) ([c154fc8](https://github.com/jorisdugue/nw-builder/commit/c154fc8a2c020311610897485259c3b2b44a2259))
* **compressing:** use `yauzl-promise` if platform and build is MacOS ([#973](https://github.com/jorisdugue/nw-builder/issues/973)) ([7abc6c7](https://github.com/jorisdugue/nw-builder/commit/7abc6c7d457c6b7171faaffe0ae0e250716b1ad7))
* **compression:** resolve promise in close event ([#698](https://github.com/jorisdugue/nw-builder/issues/698)) ([cf99bed](https://github.com/jorisdugue/nw-builder/commit/cf99bed43926e199fe62ce394eff8c047dbce319))
* **config:** update entry point ([5969a1b](https://github.com/jorisdugue/nw-builder/commit/5969a1bb64a07d919b8bbc161b8c52cf3939b8ab))
* copy ffmpeg to correct path after extract ([#918](https://github.com/jorisdugue/nw-builder/issues/918)) ([675ca68](https://github.com/jorisdugue/nw-builder/commit/675ca686a397a09b5cb5bfac6cec406610013857))
* copy nw and app files correctly ([f1ce19f](https://github.com/jorisdugue/nw-builder/commit/f1ce19fea8baf400334c445229b168493ff9dfab)), closes [#806](https://github.com/jorisdugue/nw-builder/issues/806)
* correct notify util ([#767](https://github.com/jorisdugue/nw-builder/issues/767)) ([5fa3582](https://github.com/jorisdugue/nw-builder/commit/5fa358292a90fbb8b06342b244a6a72e10ba75d3))
* correct nwbuild validation logic ([#769](https://github.com/jorisdugue/nw-builder/issues/769)) ([81b4c61](https://github.com/jorisdugue/nw-builder/commit/81b4c61e2be4eb8022af99b4f9f3a3e7ac08b601))
* create `cacheDir` and `outDir` before getting release info ([#772](https://github.com/jorisdugue/nw-builder/issues/772)) ([15b94c0](https://github.com/jorisdugue/nw-builder/commit/15b94c0ca6f5eeceef854987decbad654cb67adc))
* **decompress:** migrate from `decompress` from to `compressing` ([#879](https://github.com/jorisdugue/nw-builder/issues/879)) ([fddf6fa](https://github.com/jorisdugue/nw-builder/commit/fddf6fa73ee77ebd6fe0aa0a59b3a733cb427ecd))
* **deps:** remove breaking `thenify` ([#572](https://github.com/jorisdugue/nw-builder/issues/572)) ([d985bf6](https://github.com/jorisdugue/nw-builder/commit/d985bf6160adcb7c46de0e9c29bf94224f02af6f))
* desktop entry file ([#690](https://github.com/jorisdugue/nw-builder/issues/690)) ([6ab3baa](https://github.com/jorisdugue/nw-builder/commit/6ab3baaaa48fb09f00c5e59dacc4e49153533a7e))
* **docs:** base config ([1211abf](https://github.com/jorisdugue/nw-builder/commit/1211abfc3068068be9ac0390610a507ea5fb18ae))
* **docs:** changelog, docs, release ([2b54f18](https://github.com/jorisdugue/nw-builder/commit/2b54f1854a87e4cc5360d5a3193091a697b05773))
* **docs:** clarify `mode` option usage ([1ef6664](https://github.com/jorisdugue/nw-builder/commit/1ef666443c6b8be17971cdffa2f91573bc2f172e))
* **docs:** rename issue template ([95e78f6](https://github.com/jorisdugue/nw-builder/commit/95e78f6a6aacd2d31364acb1d1b3dd63335e6b7e))
* **docs:** update versions, fix broken links ([#555](https://github.com/jorisdugue/nw-builder/issues/555)) ([b96d47d](https://github.com/jorisdugue/nw-builder/commit/b96d47d8ba22e5a53576b0b470565fe419968c3c))
* **docs:** use base URL ([fca0595](https://github.com/jorisdugue/nw-builder/commit/fca0595853c273b5f7bfe42c7dfb2d881889fe7c))
* failure if cache dir does not exist ([#697](https://github.com/jorisdugue/nw-builder/issues/697)) ([46856bf](https://github.com/jorisdugue/nw-builder/commit/46856bfaebc81cfe2612f1aeb9e6a4982b367bac))
* ffmpeg path on some macos envs ([#922](https://github.com/jorisdugue/nw-builder/issues/922)) ([40b8e59](https://github.com/jorisdugue/nw-builder/commit/40b8e593b6abec65b4b833138825d9c1be89b6fb))
* file globbing ([#818](https://github.com/jorisdugue/nw-builder/issues/818)) ([7336912](https://github.com/jorisdugue/nw-builder/commit/7336912e9a8a9a186674979b030a4ee124eb38b0))
* file globing ([#785](https://github.com/jorisdugue/nw-builder/issues/785)) ([38dc4a6](https://github.com/jorisdugue/nw-builder/commit/38dc4a6798d2a70ccd5cf63e09e5584910cd0b6f))
* **fs:** preserve relative symbolic links by adding `verbatimSymLinks` to `cp` operation ([#880](https://github.com/jorisdugue/nw-builder/issues/880)) ([63d3b9e](https://github.com/jorisdugue/nw-builder/commit/63d3b9ed2fb7efa90d4dade3770e10a43e8fe3cd))
* **fs:** preserve relative symlinks of NW.js files ([#883](https://github.com/jorisdugue/nw-builder/issues/883)) ([48fc77e](https://github.com/jorisdugue/nw-builder/commit/48fc77e5d5725e0e4ea297260abd2f69487cc99c))
* get mode ([#827](https://github.com/jorisdugue/nw-builder/issues/827)) ([bf8a0fe](https://github.com/jorisdugue/nw-builder/commit/bf8a0fea70e77446463805f35bfcb6dac18441a2))
* **get:** `FFmpeg` decompression ([#962](https://github.com/jorisdugue/nw-builder/issues/962)) ([f05b386](https://github.com/jorisdugue/nw-builder/commit/f05b386e9c2cf7f2b39bdd9d3ca3cb842e89a494))
* **get:** cache ffmpeg ([#944](https://github.com/jorisdugue/nw-builder/issues/944)) ([51368bc](https://github.com/jorisdugue/nw-builder/commit/51368bc3f533acba0ddb1be99c972011d4c2b9a1))
* **get:** correctly pass options to function ([#953](https://github.com/jorisdugue/nw-builder/issues/953)) ([1ed0ac2](https://github.com/jorisdugue/nw-builder/commit/1ed0ac21f8d3e42a79ef5b5c5b397c5cfa2c3c5f))
* **get:** default import ([379e870](https://github.com/jorisdugue/nw-builder/commit/379e870e75a3598a0bc937f1c0c678392f0c6ba3))
* **get:** migrate from `unzipper` to `yauzl-promise` to prevent corrupting files ([#1015](https://github.com/jorisdugue/nw-builder/issues/1015)) ([673985e](https://github.com/jorisdugue/nw-builder/commit/673985e5e0b360bca44ff5ec8f1782ea947c0c9e)), closes [#1002](https://github.com/jorisdugue/nw-builder/issues/1002) [#1000](https://github.com/jorisdugue/nw-builder/issues/1000)
* **get:** restore symlinks on unzip on `MacOS` ([#924](https://github.com/jorisdugue/nw-builder/issues/924)) ([7a3e356](https://github.com/jorisdugue/nw-builder/commit/7a3e3565e393e87fa0d6cfd62742220ab77939f4))
* **get:** return promise to await correctly ([#906](https://github.com/jorisdugue/nw-builder/issues/906)) ([275b4ab](https://github.com/jorisdugue/nw-builder/commit/275b4abc38e5f5d63385e2797515242c35b9b02a))
* **get:** wrap `unzipper` in Promise ([#999](https://github.com/jorisdugue/nw-builder/issues/999)) ([735d228](https://github.com/jorisdugue/nw-builder/commit/735d228f1bdc196865aa9cb5d7ca822fc8936e8d))
* glob file and dir differently ([4e2d5af](https://github.com/jorisdugue/nw-builder/commit/4e2d5af29b18589faa19006b6b0670a6f4bd91ff))
* **glob:** do not resolve `options.srcDir` when parsing `options` object  ([#878](https://github.com/jorisdugue/nw-builder/issues/878)) ([0c8aceb](https://github.com/jorisdugue/nw-builder/commit/0c8aceb0360afb5bc6125415206c4d30d00cd3ab))
* **lib:** add `callback` array to `nwbuild` function ([25843fd](https://github.com/jorisdugue/nw-builder/commit/25843fda7a0675e6b949471650bda0bd51716a1a))
* **lib:** execute async function ([fce5945](https://github.com/jorisdugue/nw-builder/commit/fce5945408d57a1cf9b8f97bf28e5c906976d8e7))
* mac and windows build ([#650](https://github.com/jorisdugue/nw-builder/issues/650)) ([f647de0](https://github.com/jorisdugue/nw-builder/commit/f647de098ddfc0ef400ea8041be2cedc4be3622a))
* macOS unzip ([#975](https://github.com/jorisdugue/nw-builder/issues/975)) ([c02566e](https://github.com/jorisdugue/nw-builder/commit/c02566e6da247309416c8a0ad1ac5ec05a0f6711))
* missing symlinks in macos ([#990](https://github.com/jorisdugue/nw-builder/issues/990)) ([8ab84ea](https://github.com/jorisdugue/nw-builder/commit/8ab84eadd213bccecd41f9f8c53518b933a7b11c))
* module imports ([2b16a3c](https://github.com/jorisdugue/nw-builder/commit/2b16a3c2ebe77dbca5d8a42d3df041da36b5d788))
* move all messages to debug log level ([#703](https://github.com/jorisdugue/nw-builder/issues/703)) ([9f444c9](https://github.com/jorisdugue/nw-builder/commit/9f444c98ee5fecf85c8ea818dc1cdb02625c3486))
* move ffmpeg to correct folder after extract ([#917](https://github.com/jorisdugue/nw-builder/issues/917)) ([6e8cef6](https://github.com/jorisdugue/nw-builder/commit/6e8cef6610d6055b16efc9e23ac4114d335eee7a))
* order imports ([5038500](https://github.com/jorisdugue/nw-builder/commit/50385002c12e2230afcf87c7a1932eb7c3acc5b8))
* **osx:** set `NSHumanReadableCopyright` property ([#904](https://github.com/jorisdugue/nw-builder/issues/904)) ([03fda3f](https://github.com/jorisdugue/nw-builder/commit/03fda3fd0dc518412a7ef0a46d1dbe4e6376eb4d))
* package.json to reduce vulnerabilities ([dd1e8a5](https://github.com/jorisdugue/nw-builder/commit/dd1e8a5d596d35f22b8369ddb9047f12a8021009))
* **platform:** add osx multiple locale support ([#389](https://github.com/jorisdugue/nw-builder/issues/389)) ([3388a73](https://github.com/jorisdugue/nw-builder/commit/3388a73b4738aff3ad722f3809303f3edc34d39f))
* prevent nuking `options.app`, use absolute path for `rcedit` ([#815](https://github.com/jorisdugue/nw-builder/issues/815)) ([ff8f4e7](https://github.com/jorisdugue/nw-builder/commit/ff8f4e70efe121b4975f3d09e056556c5bd2eb72))
* remove `outDir` directory if `options.zip` is true ([#889](https://github.com/jorisdugue/nw-builder/issues/889)) ([90afc6e](https://github.com/jorisdugue/nw-builder/commit/90afc6ead4675fa3ae39df98c8c360db2554d7a6))
* remove test impl for run mode ([f4d0173](https://github.com/jorisdugue/nw-builder/commit/f4d01738ef17f5c35f3a0336b72974ac2f23179d))
* rename executable using `options.app.name` ([295fa0d](https://github.com/jorisdugue/nw-builder/commit/295fa0d8a48b8b835d127f9a0b845dcb41b94193)), closes [#881](https://github.com/jorisdugue/nw-builder/issues/881)
* rename nw exe ([#712](https://github.com/jorisdugue/nw-builder/issues/712)) ([1a49aeb](https://github.com/jorisdugue/nw-builder/commit/1a49aeb7dc40f608af55ff5ec5be359384b6e3a1))
* resolve file path after checking path type ([97055c4](https://github.com/jorisdugue/nw-builder/commit/97055c438147ffe8e6a36f644068119217dc30e2)), closes [#807](https://github.com/jorisdugue/nw-builder/issues/807)
* **resource:** set windows icon with rcedit ([#566](https://github.com/jorisdugue/nw-builder/issues/566)) ([43c0383](https://github.com/jorisdugue/nw-builder/commit/43c03831e26c29ab03cd124da94f1948d178c05c))
* run mode options ([#718](https://github.com/jorisdugue/nw-builder/issues/718)) ([8af9bab](https://github.com/jorisdugue/nw-builder/commit/8af9babc43d898ff20910f003d6435667bfd2ed8))
* **run:** parse options.argv correctly ([#946](https://github.com/jorisdugue/nw-builder/issues/946)) ([60790fa](https://github.com/jorisdugue/nw-builder/commit/60790fab4c760acdd84b4327a98802e298532deb))
* set `files` to `options.srcDir`  if glob disabled ([#830](https://github.com/jorisdugue/nw-builder/issues/830)) ([56cf9b2](https://github.com/jorisdugue/nw-builder/commit/56cf9b2ea2df4d6b8272be6cba59ee17698b0b09))
* **test:** disable glob in chromedriver tests ([#907](https://github.com/jorisdugue/nw-builder/issues/907)) ([4ded67d](https://github.com/jorisdugue/nw-builder/commit/4ded67daba31021ab637d209cc455de2413402ee))
* **test:** false positives while building and running demo app ([#781](https://github.com/jorisdugue/nw-builder/issues/781)) ([8c6af3d](https://github.com/jorisdugue/nw-builder/commit/8c6af3d13ce100d28fe86905cb35c2e8abc37fea))
* **types:** align type definitions with docs ([#956](https://github.com/jorisdugue/nw-builder/issues/956)) ([3b3ac27](https://github.com/jorisdugue/nw-builder/commit/3b3ac2743e9f47df02fb5f69cbacb30819839c96))
* typo ([#773](https://github.com/jorisdugue/nw-builder/issues/773)) ([25fc923](https://github.com/jorisdugue/nw-builder/commit/25fc923549c7b9fdcd9f2cc95f68908f2bfe84d8))
* **utils:** add back `chmod` ([17a7a38](https://github.com/jorisdugue/nw-builder/commit/17a7a38c76cfbf015768af478618087448afb390))
* **utils:** do not append `Version` before `CFBundleShortVersionString` ([#576](https://github.com/jorisdugue/nw-builder/issues/576)) ([6282f27](https://github.com/jorisdugue/nw-builder/commit/6282f27e26499ae835450b4f9f6296d0d9071000))
* **utils:** don't change binary file permissions ([fe8b535](https://github.com/jorisdugue/nw-builder/commit/fe8b535d39b222f4657f8d2e62385029dbe08593))
* **utils:** only read files called `package.json` ([#600](https://github.com/jorisdugue/nw-builder/issues/600)) ([ed4eee1](https://github.com/jorisdugue/nw-builder/commit/ed4eee1d1b5de3696d6bdeedf6a47f44787127cd))
* **utils:** typo ([c0c6092](https://github.com/jorisdugue/nw-builder/commit/c0c6092b38b4d125348e16ac49bc3b50856e29c1))
* validate version ([#835](https://github.com/jorisdugue/nw-builder/issues/835)) ([68d3593](https://github.com/jorisdugue/nw-builder/commit/68d35934a7a4fef0c5156c82ec6b9071a8a39bc3))
* **win-bld:** skip modify exe if platform is not windows or wine is not installed ([#739](https://github.com/jorisdugue/nw-builder/issues/739)) ([cb5f0f9](https://github.com/jorisdugue/nw-builder/commit/cb5f0f9378d419debe162c2df2589ea84dc34d3a))
* **win:** enable icon ([#905](https://github.com/jorisdugue/nw-builder/issues/905)) ([547e90c](https://github.com/jorisdugue/nw-builder/commit/547e90cae52e2d1f8e0828e9ae2e1d5bc650cb0b))
* **yargs:** specify arguments types ([#901](https://github.com/jorisdugue/nw-builder/issues/901)) ([daff3f8](https://github.com/jorisdugue/nw-builder/commit/daff3f8a3e0843fd45742af9c248b0eec5e05be0))

## [4.6.0](https://github.com/nwutils/nw-builder/compare/v4.5.4...v4.6.0) (2024-02-01)


### Features

* **get:** set `cacheDir` on another volume ([#1023](https://github.com/nwutils/nw-builder/issues/1023)) ([7c0f711](https://github.com/nwutils/nw-builder/commit/7c0f711d407c4f992e7897e9d590f03d3105db4e)), closes [#1017](https://github.com/nwutils/nw-builder/issues/1017)

## [Unreleased]

## [4.5.4] - 2024-01-23

### Changed

- Migrate from `unzipper` to `yauzl-promise` to prevent corrupting files. 

## [4.5.3] - 2023-12-20

### Changed

- Wrap `unzipper` call inside Promise to prevent race condition.

## [4.5.2] - 2023-12-19

### Changed

- Fix `yargs/helpers` import for cli usage.

## [4.5.1] - 2023-12-19

### Changed

- Manually create symbolic links for MacOS builds.

## [4.5.0] - 2023-12-18

## Added

- Use `unzipper` to decompress ZIP files.

## Changed

- Use `tar` to extract tarballs.
- Disable `options.nativeAddon`.

### Removed

- Remove `yauzl-promise` since it does not preserve symlinks on MacOS.

## [4.4.2-beta.4] - 2023-11-03

### Changed

- Use `yauzl-promise` to decompress MacOS build on MacOS platform.

### Removed

- Native package `unzip` usage.

## [4.4.2-beta.3] - 2023-10-23

### Added

- Align cache implementation with `nwjs/npm-installer`
- `nw` module can [use the `options.cacheDir`](https://github.com/nwjs/npm-installer#retrieve-binaries-from-custom-download-location-or-file-path) to get cached NW.js binaries.

## [4.4.2-beta.2] - 2023-10-20

### Added

- Node Native Addon support using GYP. To enable, set `options.nativeAddon` to `gyp`.

## [4.4.2-beta.1] - 2023-10-16

### Added

- Managed Manifest mode. `options.ManagedManifest` defaults to `false`.
- If `true`, then first `package.json` globbed is parsed as manifest.
- If JSON type, object is parsed as manifest.
- If string type, then resolve as file path to manifest.

## [4.4.2] - 2023-10-16

### Changed

- Fix FFmpeg decompression.
- Auto generate docs from JSDoc comments.
- Improve TypeScript type definitions.
- Fix get mode.
- Refactor build mode.
- Generate markdown docs from JSDocs.

## [4.4.1] - 2023-09-06

### Changed

- Improve debug logging.
- Fixed handling of argv.

## [4.4.0] - 2023-09-05

### Added

- Cache community FFmpeg.
- Move FFmpeg decompress function to relevant location

## [4.3.11] - 2023-09-05

### Changed

- Separate download logic for NW.js and FFmpeg.

## [4.3.10] - 2023-08-21

### Removed

- Do not copy the first `package.json` encountered to the root of `options.outDir` when `options.glob` is enabled. This may seem like a breaking change but it is actually reverting incorrect behaviour.

## [4.3.9] - 2023-08-15

### Changed

- Some mac environments don't restore symlinks when using compressing lib. Now we will use system `unzip` command to extract zip files

## [4.3.8] - 2023-08-14

### Changed

- Handle error during ffmpeg copy on some mac environments

## [4.3.7] - 2023-08-11

### Changed

- Move community `ffmpeg` in the correct folder.

## [4.3.6] - 2023-08-11

### Changed

- Move community `ffmpeg` in the correct folder.

## [4.3.5] - 2023-08-03

### Changed

- Return promise in get mode to await it correctly.

## [4.3.4] - 2023-08-02

### Changed

- Conditonally set Icon for Windows build.
- Refactor `get` mode into a single file.

## [4.3.3] - 2023-07-25

### Changed

- Set `NSHumanReadableCopyright` property in `*.app/Resources/en.lproj/InfoPlist.strings` to update copyright

### Removed

- `NSHumanReadableCopyright` from `Info.plist`

## [4.3.2] - 2023-07-11

### Added

- Descriptions and argument types for remaining cli arguments.

## [4.3.1] - 2023-07-07

### Changed

- Replace the icon at `nwjs.app/Contents/Resources/app.icns` with the icon at `options.app.icon` file path.

### Removed

- `xattr` package. The `com.apple.quarantine` flag should be handled by the developer.

## [4.3.0] - 2023-07-03

### Added

- Compress `outDir` to `zip`, `tar` and `tgz` formats.
- Specify log level via `options.logLevel`.
- Add platform, arch, Node and NW.js info in debug log.
- Add MacOS name, version, description and legal metadata
- Removed redundant `options.app.icon` property (Refer to NW.js docs on how to set icon)

## [4.2.8] - 2023-06-29

### Changed

- Refactor `zip` implementation. Use `compressing` instead of `archiver` package.
- If `zip` is `true` or `"zip"`, then remove outDir after compression. (This was supposed to be the intented behavior all along).

## [4.2.7] - 2023-06-27

### Changed

- Redownload `manifest.json` every time the `nwbuild` function is executed.
- If `manifest.json` already exists and we are unable to connect to the `nwjs.io` domain, then use the existing manifest.
- If no `manifest.json` exists in the cache dir, then the `validate` function will cache this and throw an error - preventing the build.

## [4.2.6] - 2023-06-20

### Changed

- Preserve relative symbolic links of NW.js files during build mode

## [4.2.5] - 2023-06-20

### Changed

- Rename executable using `options.app.name` value.

## [4.2.4] - 2023-06-18

### Changed

- Migrate from `decompress` to `compressing`

## [4.2.3-beta.2] - 2023-06-16

### Changed

- Preserve relative symbolic links during build mode

## [4.2.3-beta.1] - 2023-06-15

### Changed

- Do not resolve `options.srcDir` when parsing `options` object.

## [4.2.3] - 2023-04-19

### Changed

- Fix module imports which broke in [04ccd51](https://github.com/nwutils/nw-builder/commit/04ccd514f264f5590e5f86c42288904fe027901f)

## [4.2.2] - 2023-04-14

### Added

- Validation for `options.version`.
- Type definition file for `nwbuild` function.

## [4.2.1] - 2023-03-28

### Changed

- Set `files` to `options.srcDir` if glob disabled preventing a `package.json` not found error.

## [4.2.0] - 2023-03-27

## Added

- Glob flag defaulting to true. Currently file globbing is broken and it is recommended to set `glob` to false.

### Changed

- Fixed `get` mode
- Fixed `run` mode
- Fixed `build` mode
- Updated `get` mode docs

## [4.1.1-beta.2] - 2023-03-15

### Changed

- Parse the first `package.json` file and treat it as the NW.js manifest. Copy it to `outDir/package.nw/package.json` for Linux and Windows and `outDir/nwjs.app/Contents/Resources/app.nw/package.json` for MacOS.

To simplify your workflow, you can pass the path to the `package.json` first:

```shell
nwbuild ./path/to/package.json ./app/**/* ./node_modules/**/*
```

Make sure your manifest file's `main` property points to a valid file path. In this case it might be:

```json
{
  "main": "app/index.html"
}
```

## [4.1.1-beta.1] - 2023-03-14

### Added

- `get` mode to only download NW.js binaries. Example use case: download during Node's `postinstall` hook:

```json
{
  "scripts": {
    "postinstall": "nwbuild --mode=get --flavor=sdk"
  }
}
```

- Check if NW.js's Node version matches host's Node version

## Changed

- Fix undefined import for Windows configuration

## [4.1.1-beta.0] - 2023-03-12

### Changed

- Remove false test for run mode.

## [4.1.1] - 2023-03-12

### Changed

- Glob file and directory differently.
- MacOS ARM build is no longer behind `beta` version.

## [4.1.0-beta.3] - 2023-03-01

### Added

- Allow list `https://npmmirror.com/mirrors/nwjs/` and `https://npm.taobao.org/mirrors/nwjs/` mirrors.

## [4.1.0-beta.2] - 2023-02-29

### Changed

- Do not convert srcDir files to absolute paths.
- Copy files to correct location.

## [4.1.0-beta.1] - 2023-02-28

### Changed

- Resolve path iff file path type is valid.

## [4.1.0-beta.0] - 2023-02-25

### Added

- MacOS ARM support

## [4.1.0] - 2023-02-23

## Added

- Use (community) prebuilt version of `ffmpeg` if the `ffmpeg` flag is `true` (defaults to `false`).

### Changed

- `await` platform specific config steps

## [4.0.11] - 2023-02-5

### Changed

- Security update `http-cache-semantics` to `v4.1.1`.

## [4.0.10] - 2023-02-05

### Added

- `options.cli` flag to prevent `node-glob` from globbing already globbed files and erroring out with a `package.json not found in srcDir file glob patterns` message.

### Changed

- Copy subdirectories of `options.srDir` in the correct location.

## [4.0.9] - 2023-02-03

### Added

- Run and build demo app in CI.

### Changed

- Fixed false positives in CI
- Throw errors instead of returning them
- Reject error object instead of exit code

## [4.0.8] - 2023-01-15

### Added

- Flag to check if specific `nw` release is cached. [#772](https://github.com/nwutils/nw-builder/pull/772)

### Changed

- Create `cacheDir`, `outDir` before getting release info. [#772](https://github.com/nwutils/nw-builder/pull/772)

## [4.0.7] - 2023-01-14

### Changed

- Do not throw error if `nwbuild` is of `object` type. [#769](https://github.com/nwutils/nw-builder/pull/769)

- Fix `package.json` path for `updateNotifier`. [#767](https://github.com/nwutils/nw-builder/pull/767)

## [4.0.6] - 2023-01-09

### Added

- Warn about loss of permissions if building Linux or MacOS on Windows. [8793d4b](https://github.com/nwutils/nw-builder/commit/8793d4bf06288199fcaff340fda43c1e2fbcacbc)

### Changed

- Fix error when `options.version` is `latest`. [33ef184](https://github.com/nwutils/nw-builder/commit/33ef184467f78fed94541e876da042b4ed99d443)

### Removed

- CJS support [968f798](https://github.com/nwutils/nw-builder/commit/968f7980de59fea72ddac8e1d64628e561de1f9a)

## [4.0.5] - 2023-01-06

### Changed

- Prevent duplicate globbing of `srcDir` files. [07901c9](https://github.com/nwutils/nw-builder/commit/07901c9e3930481ead0977b9be731765df28c087)

## [4.0.4] - 2023-01-06

### Changed

- Convert `srcDir` type from `string[]` to `string`. [1a699af](https://github.com/nwutils/nw-builder/commit/1a699af300782e0847333bb7ad945dbde8940350)

## [4.0.3] - 2023-01-06

### Added

- File globing. [#749](https://github.com/nwutils/nw-builder/pull/749)

- Linux and Windows configuration options. [#729](https://github.com/nwutils/nw-builder/pull/729)

### Changed

- Skip modification of Windows executable if platform is not Windows or Wine is not installed. [#739](https://github.com/nwutils/nw-builder/pull/739)

- Run mode should only require `srcDir`, `version` and `flavor`. [#718](https://github.com/nwutils/nw-builder/pull/718)

## [4.0.2] - 2022-11-30

### Added

- Allow user to rename NW executable. [#712](https://github.com/nwutils/nw-builder/pull/712)

### Changed

- Fix MacOS build. [#717](https://github.com/nwutils/nw-builder/pull/717)

- CJS support via `esbuild`. [#713](https://github.com/nwutils/nw-builder/pull/713)

## [4.0.1] - 2022-11-20

### Added

- Support for Desktop Entry file. [#690](https://github.com/nwutils/nw-builder/pull/690)

### Changed

- Resolve promise in `close` event with respect to compression. [#698](https://github.com/nwutils/nw-builder/pull/698)

- Check for release info after downloading NW binaries in `cacheDir`. [#697](https://github.com/nwutils/nw-builder/pull/697)

## [4.0.0] - 2022-11-16

### Added

- Rename Helper apps. [#687](https://github.com/nwutils/nw-builder/pull/687)

- MacOS support. [#685](https://github.com/nwutils/nw-builder/pull/685)

- Check for `nwbuild` object in `package.json`. [#684](https://github.com/nwutils/nw-builder/pull/684)

## [3.8.6] - 2022-09-22

- Fix mac and windows build

## [3.8.5] - 2022-09-20

### Added

- `nwbuild` function which accidently got removed.

### Changed

- Update usage docs for `nwbuild`

## [3.8.4] - 2022-09-20

### Changed

- Refactor download function

## [3.8.3-beta.1]

### Changed

- Check for first instance of `package.json`

## [3.8.3] - 2022-08-26

### Changed

- `platforms` argument also accepts comma separated (without spaces) values

## [3.8.2] - 2022-08-08

### Added

- Support for multiple file paths

## [3.8.1] - 2022-07-18

### Changed

- Fix regex to match `package.json` _files_ only

## [3.8.0] - 2022-07-11

## Added

- `mode` option which defaults to run
- `nwbuild` function
- `quiet` option to documentation

## Changed

- CLI options by matching them to the API

## [3.7.4] - 2022-06-06

## Removed

- Remove `Version` from `CFBundleShortVersionString` [#576](https://github.com/nwjs-community/nw-builder/pull/576)

## [3.7.2] - 2022-06-02

## Added

- Added options `buildType`, `macCredits`, `macPlist`, `zip`, `zipOptions` to CLI [#575](https://github.com/nwjs-community/nw-builder/pull/575)

## Changed

- Update lint command [#575](https://github.com/nwjs-community/nw-builder/pull/575)

## [3.7.1] - 2022-06-02

## Changed

- Add `EditorConfig` [#574](https://github.com/nwjs-community/nw-builder/pull/574)
- Fix build step for Windows x64 platform [#572](https://github.com/nwjs-community/nw-builder/pull/572)
- Refactor `platforms` object [#571](https://github.com/nwjs-community/nw-builder/pull/571)

## [3.7.0] - 2022-05-30

## Added

- Optional zip file merging for Windows and Linux [#567](https://github.com/nwjs-community/nw-builder/pull/567)
- Add code of conduct [#560](https://github.com/nwjs-community/nw-builder/pull/560)

## Changed

- Update contributing guide [#569](https://github.com/nwjs-community/nw-builder/pull/569)
- Switch from TypeScript to JSDocs [#568](https://github.com/nwjs-community/nw-builder/pull/568)
- Set window icon with `rcedit` [#566](https://github.com/nwjs-community/nw-builder/pull/566)
- Refactor `checkCache` [#565](https://github.com/nwjs-community/nw-builder/pull/565)
- Simplify demo
- Refactor `detectCurrentPlatform` [#564](https://github.com/nwjs-community/nw-builder/pull/564)
- Update dependencies [#561](https://github.com/nwjs-community/nw-builder/pull/561) [#532](https://github.com/nwjs-community/nw-builder/pull/532)

## Removed

## [3.6.0] - 2022-05-18

### Added

- GitHub Actions for CICD [#552](https://github.com/nwjs-community/nw-builder/pull/552)
- Support multiple locales on OSX [#389](https://github.com/nwjs-community/nw-builder/pull/389)
- Pull request and issue template [#553](https://github.com/nwjs-community/nw-builder/pull/553)

### Changed

- Dependencies [#550](https://github.com/nwjs-community/nw-builder/pull/550)
- Documentation [#540](https://github.com/nwjs-community/nw-builder/pull/540) [#553](https://github.com/nwjs-community/nw-builder/pull/553) [#555](https://github.com/nwjs-community/nw-builder/pull/555)
- Improve run mode by detecting current platform to prevent downloading additional binaries

### Removed

- Travis
- AppVeyor
- JSHint
- EditorConfig

## [3.5.7]

### Security

- Source platform overrides module into the project instead of it being an extenal dependency. This helped us get rid of a vulnerable lodash version. See https://github.com/nwjs-community/nw-builder/issues/500

## [3.5.1] - 2017-10-19

### Added

- Add option.winVersionString for accurate process name. See https://github.com/nwjs-community/nw-builder/pull/459.

### Fixed

- Small platform overrides fix. See https://github.com/nwjs-community/nw-builder/pull/477/files.

## [3.4.1] - 2017-06-05

### Removed

- The `bluebird` dependency. We're now using native promises instead.

## [3.4.0] - 2017-05-28

### Added

- If using the package programmatically and it's out of date, a message will be shown (this was always the case for the CLI).
- There is now a README in every directory (with at least a single sentence summarizing the directory) to help with onboarding contributors.

### Changed

- Some dependencies are updated.

### Removed

- `osx32` is removed from the default list of platforms. Thanks to [@preaction](https://github.compreaction) (PR [#439](https://github.com/nwjs-community/nw-builder/pull/439)).
- An unnecessary `rcedit` dependency is removed.

### Fixed

- For Node 7+ users, you won't see a `os.tmpDir` deprecation warning anymore.

---

## Old format

- 2017-05-22 `3.2.3` Fix for caching when a version is specified (thanks @piwonesien for the help).
- 2017-05-20 `3.2.2` Fix: when using the `nwbuild` in run mode, the `-p` option was ignored and the current platform was always used.
- 2017-05-16 `3.2.1` Fix: NW.js 0.22.0+ apps didn't open.
- 2017-02-12 `3.2.0` Defaults to HTTPS now, added `manifestUrl` option, and bumped some dependencies.
- 2016-10-09 `3.1.2` Fix for passing array as files option when running app (plus some security fixes).
- 2016-10-09 `3.1.1` Fix for flavor feature when using CLI.
- 2016-09-14 `3.1.0` Ability to select any flavor of NW.js, not just `sdk`.
- 2016-08-28 `3.0.0` bumping graceful-fs-extra dependency to 2.0.0.
- 2016-08-14 `2.2.7` fix for macIcns option when using NW.js 0.12.3
- 2016-07-31 `2.2.6` fix for OS X caching
- 2016-07-03 `2.2.5` fix for update-notifier usage in bin
- 2016-07-03 `2.2.4` fix for syntax error in CLI
- 2016-07-02 `2.2.3` a few small fixes for the run option and more
- 2016-07-02 `2.2.2` fix for cache check of some legacy versions
- 2016-07-02 `2.2.1` supports newer NW.js versions (via http://nwjs.io/versions.json), plus other fixes.
- 2015-12-18 `2.2.0` added `zip` option.
- 2015-12-06 `2.1.0` added `cacheDir` command-line option, fix for no info being passed back, etc.
- 2015-06-28 `2.0.2` put upper bound to semver check for windows.
- 2015-06-14 `2.0.1` safer validation of versions.
- 2015-06-14 `2.0.0` changed to nw-builder, etc.
- 2015-05-05 `1.0.12` when using latest NW.js version, it's first validated that it's not an alpha version (fixes [#222](https://github.com/nwjs/nw-builder/issues/222)). Plus a fix for the `winIco` & `macIcns` command line options
- 2015-01-29 `1.0.8` fixed EMFILE errors (see [#147](https://github.com/nwjs/nw-builder/issues/147) [#148](https://github.com/nwjs/nw-builder/pull/148))
- 2015-01-21 `1.0.7` fixed about screen when copyright is not supplied
- 2015-01-15 `1.0.6` fixed downloads for nw.js version 0.12.0-alpha1
- 2015-01-15 `1.0.5` fixed downloads for NW.js versions < 0.12.0-alpha
- 2014-12-12 `1.0.0` 64-bit support, improved platform-overrides and no more EMFILE errors.
- 2014-12-07 `0.4.0` macPlist CFBundleIdentifier is generated from `package.json` (see [#131](https://github.com/nwjs/nw-builder/pull/131))
- 2014-11-14 `0.3.0` macPlist option improvements (see [#96](https://github.com/nwjs/nw-builder/pull/96))
- 2014-10-30 `0.2.0` adds support for platform-specific manifest overrides (see [#94](https://github.com/nwjs/nw-builder/pull/94))
- 2014-08-19 `0.1.2` adds a progress bar to downloads, fixes downloading through a proxy, fixed winIco, bug fixes
- 2014-08-01 `0.1.0` use app filename for generated executables, optimized version checking, (known issue: `winIco` on windows)
- 2014-07-31 `0.0.4` fixed compatibility with nodewebkit 0.10.0
- 2014-04-20 Added run option, bug fixes
- 2014-04-13 Preview Release
