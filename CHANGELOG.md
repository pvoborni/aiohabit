# Changelog

<!--next-version-placeholder-->

## v0.6.0 (2021-01-27)
### Feature
* Podman support in SSH action ([`10a43f1`](https://github.com/neoave/mrack/commit/10a43f1bdaa328fad0a4fb2ad4ae57cd7ef41878))
* Podman support in Ansible inventory ([`f5dbed9`](https://github.com/neoave/mrack/commit/f5dbed9fc61ab474220fbc655246e1aafe03f73b))
* Add Podman provider ([`ef35545`](https://github.com/neoave/mrack/commit/ef3554547eada23a65f0d40b7ecd9f51cb17eeeb))

### Fix
* Handle ServerError in OpenStack provisioning ([`46048c0`](https://github.com/neoave/mrack/commit/46048c01f6ae3224e9d49e711e610b28497f63df))
* More verbose print about available networks ([`824b359`](https://github.com/neoave/mrack/commit/824b3594d152b061c36ade3f382b8908272030f9))

## v0.5.2 (2020-12-21)
### Fix
* Mrack eh add no longer complains about coroutine 'eh' not awaited ([`7dbdd6a`](https://github.com/neoave/mrack/commit/7dbdd6a6f54331078907081527c944dd5899ab19))
* Error for non authorized user reading image ([`a5c355d`](https://github.com/neoave/mrack/commit/a5c355da2a0b7d37e5865fb3a78558c26b163b3f))
* Mrack.conf '~' causes no such file or directory ([`4b8dee8`](https://github.com/neoave/mrack/commit/4b8dee8d710a9a0d978561733dfcd898d96c2c67))
* Load possible missing image specified in metadata ([`19103c0`](https://github.com/neoave/mrack/commit/19103c0a44311ba95409560877a48e0585795c01))

## v0.5.1 (2020-12-14)
### Fix
* Set user for Windows host in pytest-multihost config ([`e36138c`](https://github.com/neoave/mrack/commit/e36138c8f80e18eb235981ffd7eeb4840cac0855))

## v0.5.0 (2020-12-11)
### Feature
* Retry provisioning strategy ([`3683d3c`](https://github.com/neoave/mrack/commit/3683d3c20f917f57de7f88d0b3e9e4fea5ff0398))

### Fix
* Openstack: log which server is being provisioned ([`d89aa5d`](https://github.com/neoave/mrack/commit/d89aa5d20192c75560f7bb0beffb3027b0431a47))
* Pytest-multihost: handle unresolvable IP into DNS ([`56c716e`](https://github.com/neoave/mrack/commit/56c716ec910028604e2ecaf42124e7e1f6061324))
* Fix making ssh_key_filename absolute for default behavior. ([`6b5ea95`](https://github.com/neoave/mrack/commit/6b5ea951f132336fcde50b53a97c7b4338eb0099))
* Remove double status translation in parse_errors ([`e5da9cd`](https://github.com/neoave/mrack/commit/e5da9cd6403d67f75d429b3207e11555dd90e437))

## v0.4.0 (2020-12-07)
### Feature
* Output file paths configurable in mrack config ([`1761baf`](https://github.com/neoave/mrack/commit/1761baf1da0c75e8bb86ec423e3b563bdfb18871))
* Simple way to add hosts into /etc/hosts file ([`da24ac5`](https://github.com/neoave/mrack/commit/da24ac55a3189512c98884eb30f1b5a6ad4dd46a))

### Fix
* Use meta_ prefix for parent domain ([`aaeeb58`](https://github.com/neoave/mrack/commit/aaeeb58c0682dbd7be9db94dcb7469c07e6243eb))
* Add missing annotations for mypy ([`2427b15`](https://github.com/neoave/mrack/commit/2427b15ddd12b4d7813a51b3b276b8affd42259b))
* Remove deprecated flag --recursive from Makefile ([`48937f3`](https://github.com/neoave/mrack/commit/48937f38a3b8e2780d39539c513187591b9a953d))
* Move common methods to transfromer.py ([`4ea839e`](https://github.com/neoave/mrack/commit/4ea839e560a3d11662d2b65309993652b4cd44bd))
