# 0.6.3

* [Disable anti-sudo check](https://github.com/rust-lang-nursery/rustup.rs/pull/698)
* [Fixed CI toolchain pinning](https://github.com/rust-lang-nursery/rustup.rs/pull/696)

Contributors: Brian Anderson

# 0.6.2

* [Add basic autocompletion for Zsh](https://github.com/rust-lang-nursery/rustup.rs/pull/689)
* [Sort toolchains by semantic version](https://github.com/rust-lang-nursery/rustup.rs/pull/688)

Contributors: Brian Anderson, Diggory Blake, Knight, Marco A L Barbosa

# 0.6.1

* [Fix mysterious crash on OS X 10.10+](https://github.com/rust-lang-nursery/rustup.rs/pull/684)
* [Fix `component remove` command and add a test for it](https://github.com/rust-lang-nursery/rustup.rs/pull/683)

Contributors: Brian Anderson, Diggory Blake

# 0.6.0

* [Print rustup version after update](https://github.com/rust-lang-nursery/rustup.rs/pull/614)
* [Don't spawn processes for copying](https://github.com/rust-lang-nursery/rustup.rs/pull/630)
* [Upgrade error-chain to 0.3](https://github.com/rust-lang-nursery/rustup.rs/pull/636)
* [Support telemetry with lots of output](https://github.com/rust-lang-nursery/rustup.rs/pull/645)
* [Remove empty directories after component uninstall](https://github.com/rust-lang-nursery/rustup.rs/pull/634)
* [Update rustup-init.sh for powerpc](https://github.com/rust-lang-nursery/rustup.rs/pull/647)
* [Switch builds to current nightly toolchain](https://github.com/rust-lang-nursery/rustup.rs/pull/651)
* [Add a WIP MSI installer](https://github.com/rust-lang-nursery/rustup.rs/pull/635)
* [Add `--path` and `--nonexistent` options to `rustup override unset`](https://github.com/rust-lang-nursery/rustup.rs/pull/650)
* [Add `component` subcommand](https://github.com/rust-lang-nursery/rustup.rs/pull/659)

Contributors: Alex Crichton, Brian Anderson, Diggory Blake, Ivan Nejgebauer Josh
Machol, Julien Blanchard, Patrick Reisert, Ri, Tim Neumann

# 0.5.0

* [List custom toolchains in `rustup show`](https://github.com/rust-lang-nursery/rustup.rs/pull/620)
* [Add a usage example for local builds](https://github.com/rust-lang-nursery/rustup.rs/pull/622)
* [Read/Write impl rework for rustls](https://github.com/rust-lang-nursery/rustup.rs/pull/592)
* [Introduce `+TOOLCHAIN` syntax for proxies](https://github.com/rust-lang-nursery/rustup.rs/pull/615)
* [Add `rustup man`](https://github.com/rust-lang-nursery/rustup.rs/pull/616)
* [Try detecting sudo when running `rustup-init`](https://github.com/rust-lang-nursery/rustup.rs/pull/617)
* [Handle active custom toolchain in `rustup show`](https://github.com/rust-lang-nursery/rustup.rs/pull/621)

Contributors: Brian Anderson, Cam Swords, Daniel Keep, Diggory Blake,
Florian Gilcher, Ivan Nejgebauer, theindigamer

# 0.4.0

* [Improve rustls CA certificate loading](https://github.com/rust-lang-nursery/rustup.rs/pull/585)
* [Detect ARMv7 CPUs without NEON extensions and treat as ARMv6](https://github.com/rust-lang-nursery/rustup.rs/pull/593)
* [Allow any toolchain to be specified as the default during rustup installation](https://github.com/rust-lang-nursery/rustup.rs/pull/586)
* [Add details about updating rustup to README](https://github.com/rust-lang-nursery/rustup.rs/pull/590)
* [Update libbacktrace to generate less filesystem thrashing on Windows](https://github.com/rust-lang-nursery/rustup.rs/pull/604)
* [Update gcc dep to fix building on MSVC](https://github.com/rust-lang-nursery/rustup.rs/pull/605)
* [Remove the multirust binary](https://github.com/rust-lang-nursery/rustup.rs/pull/606)
* [Use the env_proxy crate for proxy environment variable handling](https://github.com/rust-lang-nursery/rustup.rs/pull/598)
* [Set system-specific dynamic loader env var for command execution](https://github.com/rust-lang-nursery/rustup.rs/pull/600)
* [Hide telemetry command from top level help](https://github.com/rust-lang-nursery/rustup.rs/pull/601)
* [Add the "no-self-update" feature](https://github.com/rust-lang-nursery/rustup.rs/pull/602)
* [Update to error-chain 0.2.2](https://github.com/rust-lang-nursery/rustup.rs/pull/609)
* [Add HTTP proxy documentation to README](https://github.com/rust-lang-nursery/rustup.rs/pull/610)

Contributors: Alex Crichton, Brian Anderson, Ivan Nejgebauer, Jimmy
Cuadra, Martin Pool, Wesley Moore

# 0.3.0

* [Teach rustup to download manifests from the `/staging/` directory](https://github.com/rust-lang-nursery/rustup.rs/pull/579).
* [Treat all HTTP client errors the same](https://github.com/rust-lang-nursery/rustup.rs/pull/578).
* [Remove winapi replacement](https://github.com/rust-lang-nursery/rustup.rs/pull/577).
* [Remove toolchain directory if initial toolchain install fails](https://github.com/rust-lang-nursery/rustup.rs/pull/574).
* [Fallback to old download methods if server returns 403](https://github.com/rust-lang-nursery/rustup.rs/pull/573).
* [Add preliminary rustls support](https://github.com/rust-lang-nursery/rustup.rs/pull/572).
* [Add a hack to remediate checksum failure issues](https://github.com/rust-lang-nursery/rustup.rs/pull/562).
* [Move error-chain out of tree](https://github.com/rust-lang-nursery/rustup.rs/pull/564).
* [Remove uses of subcommand synonyms in the examples](https://github.com/rust-lang-nursery/rustup.rs/pull/560).
* [Add `--yes` as alias for `-y`](https://github.com/rust-lang-nursery/rustup.rs/pull/563).
* [Remove unavailable toolchains from `target list`](https://github.com/rust-lang-nursery/rustup.rs/pull/553).
* [Add powerpc builds](https://github.com/rust-lang-nursery/rustup.rs/pull/534).
* [Fix help text for `rustup update`](https://github.com/rust-lang-nursery/rustup.rs/pull/552).
* [Remove noisy "rustup is up to date" message](https://github.com/rust-lang-nursery/rustup.rs/pull/550).
* [Fix references to non-existent `.rustup` directory](https://github.com/rust-lang-nursery/rustup.rs/pull/545).
* [When listing toolchains only list directories](https://github.com/rust-lang-nursery/rustup.rs/pull/544).
* [rustup-init: remove dependency on `file` command](https://github.com/rust-lang-nursery/rustup.rs/pull/543).
* [Link to rustup-init.sh in README](https://github.com/rust-lang-nursery/rustup.rs/pull/541).
* [Improve docs for `set default-host`](https://github.com/rust-lang-nursery/rustup.rs/pull/540).

Contributors: Alex Crichton, Brian Anderson, Drew Fisher, geemili,
Ivan Petkov, James Lucas, jethrogb, Kevin Yap, leonardo.yvens, Michael
DeWitt, Nate Mara, Virgile Andreani

# 0.2.0

* [Indicate correct path to remove in multirust upgrade instructions](https://github.com/rust-lang-nursery/rustup.rs/pull/518).
* [Bring back optional hyper with proxy support](https://github.com/rust-lang-nursery/rustup.rs/pull/532).
* ['default' and 'update' heuristics for bare triples](https://github.com/rust-lang-nursery/rustup.rs/pull/516).
* [Change upstream via $RUSTUP_DIST_SERVER](https://github.com/rust-lang-nursery/rustup.rs/pull/521).
* [Fail with a nicer error message if /tmp is mounted noexec](https://github.com/rust-lang-nursery/rustup.rs/pull/523).
* [Remove printfs from ~/.cargo/env](https://github.com/rust-lang-nursery/rustup.rs/pull/527).
* [Reduce margin in installer text to 79 columns](https://github.com/rust-lang-nursery/rustup.rs/pull/526).
* [Fix typos](https://github.com/rust-lang-nursery/rustup.rs/pull/519).
* [Fix missing curly braces in error-chain docs](https://github.com/rust-lang-nursery/rustup.rs/pull/522).
* [Fix downloads of builds without v2 manifests](https://github.com/rust-lang-nursery/rustup.rs/pull/515).
* [Explain toolchains in `help install`](https://github.com/rust-lang-nursery/rustup.rs/pull/496).
* [Compile on stable Rust](https://github.com/rust-lang-nursery/rustup.rs/pull/476).
* [Fix spelling mistakes](https://github.com/rust-lang-nursery/rustup.rs/pull/489).
* [Fix the toolchain command synonyms](https://github.com/rust-lang-nursery/rustup.rs/pull/477).
* [Configurable host triples](https://github.com/rust-lang-nursery/rustup.rs/pull/421).
* [Use a .toml file to store settings](https://github.com/rust-lang-nursery/rustup.rs/pull/420).
* [Point PATH to toolchain/bin on Windows](https://github.com/rust-lang-nursery/rustup.rs/pull/402).
* [Remove extra '.' in docs](https://github.com/rust-lang-nursery/rustup.rs/pull/472).

Contributors: Alex Crichton, benaryorg, Benedikt Reinartz, Boutin,
Michael, Brian Anderson, Diggory Blake, Erick Tryzelaar, Ivan
Nejgebauer, Jeremiah Peschka, Josh Stone, Knight, mdinger, Ryan Kung,
Tad Hardesty

# 0.1.12

* [Don't install when multirust metadata exists](https://github.com/rust-lang-nursery/rustup.rs/pull/456).

# 0.1.11

* [Actually dispatch the `rustup install` command](https://github.com/rust-lang-nursery/rustup.rs/pull/444).
* [Migrate to libcurl instead of hyper](https://github.com/rust-lang-nursery/rustup.rs/pull/434).
* [Add error for downloading bogus versions](https://github.com/rust-lang-nursery/rustup.rs/pull/428).

# 0.1.10

* [Multiple cli improvements](https://github.com/rust-lang-nursery/rustup.rs/pull/419).
* [Support HTTP protocol again](https://github.com/rust-lang-nursery/rustup.rs/pull/431).
* [Improvements to welcome screen](https://github.com/rust-lang-nursery/rustup.rs/pull/418).
* [Don't try to update non-tracking channels](https://github.com/rust-lang-nursery/rustup.rs/pull/425).
* [Don't panic when NativeSslStream lock is poisoned](https://github.com/rust-lang-nursery/rustup.rs/pull/429).
* [Fix multiple issues in schannel bindings](https://github.com/sfackler/schannel-rs/pull/1)

# 0.1.9

* [Do TLS hostname verification](https://github.com/rust-lang-nursery/rustup.rs/pull/400).
* [Expand `rustup show`](https://github.com/rust-lang-nursery/rustup.rs/pull/406).
* [Add `rustup doc`](https://github.com/rust-lang-nursery/rustup.rs/pull/403).
* [Refuse to install if it looks like other Rust installations are present](https://github.com/rust-lang-nursery/rustup.rs/pull/408).
* [Update www platform detection for FreeBSD](https://github.com/rust-lang-nursery/rustup.rs/pull/399).
* [Fix color display during telemetry capture](https://github.com/rust-lang-nursery/rustup.rs/pull/394).
* [Make it less of an error for the self-update hash to be wrong](https://github.com/rust-lang-nursery/rustup.rs/pull/372).

# 0.1.8

* [Initial telemetry implementation (disabled)](https://github.com/rust-lang-nursery/rustup.rs/pull/289)
* [Add hash to `--version`](https://github.com/rust-lang-nursery/rustup.rs/pull/347)
* [Improve download progress](https://github.com/rust-lang-nursery/rustup.rs/pull/355)
* [Completely overhaul error handling](https://github.com/rust-lang-nursery/rustup.rs/pull/358)
* [Add armv7l support to www](https://github.com/rust-lang-nursery/rustup.rs/pull/359)
* [Overhaul website](https://github.com/rust-lang-nursery/rustup.rs/pull/363)

# 0.1.7

* [Fix overrides for Windows root directories](https://github.com/rust-lang-nursery/rustup.rs/pull/317).
* [Remove 'multirust' binary and rename crates](https://github.com/rust-lang-nursery/rustup.rs/pull/312).
* [Pass rustup-setup.sh arguments to rustup-setup](https://github.com/rust-lang-nursery/rustup.rs/pull/325).
* [Don't open /dev/tty if passed -y](https://github.com/rust-lang-nursery/rustup.rs/pull/334).
* [Add interactive install, `--default-toolchain` argument](https://github.com/rust-lang-nursery/rustup.rs/pull/293).
* [Rename rustup-setup to rustu-init](https://github.com/rust-lang-nursery/rustup.rs/pull/303).
