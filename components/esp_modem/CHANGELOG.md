# Changelog


## [0.1.28](https://github.com/espressif/esp-protocols/commits/01c26c8)

### Updated

- Dual DTE support ([01c26c8](https://github.com/espressif/esp-protocols/commit/01c26c8))


## [0.1.27](https://github.com/espressif/esp-protocols/commits/44bae24)

### Updated

- Return true from on_data callback in data mode ([44bae24](https://github.com/espressif/esp-protocols/commit/44bae24))


## [0.1.26](https://github.com/espressif/esp-protocols/commits/05fff94)

### Features

- Added target test ([4314c78](https://github.com/espressif/esp-protocols/commit/4314c78))
- Add support for manual CMUX operations ([ac5d438](https://github.com/espressif/esp-protocols/commit/ac5d438), [#168](https://github.com/espressif/esp-protocols/issues/168))

### Bug Fixes

- Example to use variable mqtt topic/data ([8958d5e](https://github.com/espressif/esp-protocols/commit/8958d5e))
- Fix cmux client compilation issue ([f71192b](https://github.com/espressif/esp-protocols/commit/f71192b))
- Exit data mode only after state change ([9a7bd90](https://github.com/espressif/esp-protocols/commit/9a7bd90))
- Support AT with callback in C-API ([2180ab1](https://github.com/espressif/esp-protocols/commit/2180ab1), [#143](https://github.com/espressif/esp-protocols/issues/143))

### Updated

- update(esp_modem): Bump component version to 0.1.26 ([05fff94](https://github.com/espressif/esp-protocols/commit/05fff94), [#213](https://github.com/espressif/esp-protocols/issues/213))
- Added the missing definition for the esp_modem_set_baud function (IDFGH-9181) (#209) ([0e215b1](https://github.com/espressif/esp-protocols/commit/0e215b1))
- CI: Added coverage analyzer for esp_modem host tests ([6b684ce](https://github.com/espressif/esp-protocols/commit/6b684ce))
- Update esp_modem_command_library.cpp ([5304a6e](https://github.com/espressif/esp-protocols/commit/5304a6e))
- Added badges with version of components to the respective README files ([e4c8a59](https://github.com/espressif/esp-protocols/commit/e4c8a59))
- esp_modem/examples: Add an example to synchronise PSM sleep in Sim70XX modem and esp32. ([1ca1391](https://github.com/espressif/esp-protocols/commit/1ca1391))


## [0.1.25](https://github.com/espressif/esp-protocols/commits/f1ae14f)

### Bug Fixes

- Cleanup custom lib-commands and factory ([65c0e0e](https://github.com/espressif/esp-protocols/commit/65c0e0e))
- Examples to configure MQTT Broker ([71a2388](https://github.com/espressif/esp-protocols/commit/71a2388))
- Extend pppos example project config ([ebc36a3](https://github.com/espressif/esp-protocols/commit/ebc36a3))
- Uart Terminal read_cb race ([a02bf05](https://github.com/espressif/esp-protocols/commit/a02bf05))

### Updated

- update(esp_modem): Bump component version ([f1ae14f](https://github.com/espressif/esp-protocols/commit/f1ae14f))
- fix(esp_modem) Add example that reads GNSS info ([652314e](https://github.com/espressif/esp-protocols/commit/652314e))
- CI: fixing the files to be complient with pre-commit hooks ([945bd17](https://github.com/espressif/esp-protocols/commit/945bd17))
- Quick fix esp_modem: Added modem_console commands for deep-sleep and modem PSM. ([cf504ec](https://github.com/espressif/esp-protocols/commit/cf504ec))
- fix(esp-modem) Make simple_cmux_client example configurable ([511ed54](https://github.com/espressif/esp-protocols/commit/511ed54))
- Added modem_console commands for deep-sleep and modem PSM. ([85a2e25](https://github.com/espressif/esp-protocols/commit/85a2e25))
- ci: Compile esp_modem examples with USB support ([988b3f9](https://github.com/espressif/esp-protocols/commit/988b3f9))
- Expand PPPoS example with USB DTE ([53b5933](https://github.com/espressif/esp-protocols/commit/53b5933))
- Allow USB DTE reconnection ([bf84ae9](https://github.com/espressif/esp-protocols/commit/bf84ae9))
- Add ConsoleCommand destructor ([a89a0ab](https://github.com/espressif/esp-protocols/commit/a89a0ab))
- esp_modem_get_gnss_power_mode (#136) ([fe536e4](https://github.com/espressif/esp-protocols/commit/fe536e4))
- remove unused Config Parameters ! ([55b4775](https://github.com/espressif/esp-protocols/commit/55b4775))


## [0.1.24](https://github.com/espressif/esp-protocols/commits/9b48b0a)

### Features

- Make some CMUX params compile-time configurable ([25ac2d9](https://github.com/espressif/esp-protocols/commit/25ac2d9))

### Bug Fixes

- CMUX to ignore MSC frames ([ce175df](https://github.com/espressif/esp-protocols/commit/ce175df), [#140](https://github.com/espressif/esp-protocols/issues/140))
- Fix CRLF endlines in examples ([07a347f](https://github.com/espressif/esp-protocols/commit/07a347f))
- Console example to use configurable flow-ctrl ([d9c9681](https://github.com/espressif/esp-protocols/commit/d9c9681))

### Updated

- update(esp_modem): Bump component version ([9b48b0a](https://github.com/espressif/esp-protocols/commit/9b48b0a))
- Allow error handler register in C ([62cb235](https://github.com/espressif/esp-protocols/commit/62cb235))


## [0.1.23](https://github.com/espressif/esp-protocols/commits/04c711f)

### Features

- Add exit PPP in example ([290197c](https://github.com/espressif/esp-protocols/commit/290197c))

### Updated

- Move common C definitions in to separate header ([04c711f](https://github.com/espressif/esp-protocols/commit/04c711f))
- Minor formatting fix and spelling ([accf924](https://github.com/espressif/esp-protocols/commit/accf924))
- extended the modem_console example.  (#120) ([ef0e48a](https://github.com/espressif/esp-protocols/commit/ef0e48a))


## [0.1.22](https://github.com/espressif/esp-protocols/commits/187ef76)

### Bug Fixes

- DTE command race of timeout vs reply's signal ([a871473](https://github.com/espressif/esp-protocols/commit/a871473), [#110](https://github.com/espressif/esp-protocols/issues/110))
- Correct timeouts for certain commands ([1029078](https://github.com/espressif/esp-protocols/commit/1029078), [#129](https://github.com/espressif/esp-protocols/issues/129))
- Make get_operator_name() return also ACT value ([0015e54](https://github.com/espressif/esp-protocols/commit/0015e54), [#128](https://github.com/espressif/esp-protocols/issues/128))

### Updated

- update(esp_modem): Bump component version ([187ef76](https://github.com/espressif/esp-protocols/commit/187ef76))


## [0.1.21](https://github.com/espressif/esp-protocols/commits/d07237b)

### Updated

- Fix IDF version resolution ([d07237b](https://github.com/espressif/esp-protocols/commit/d07237b))
- Fix format warnings ([98bf3ef](https://github.com/espressif/esp-protocols/commit/98bf3ef), [#79](https://github.com/espressif/esp-protocols/issues/79))


## [0.1.20](https://github.com/espressif/esp-protocols/commits/ae8479c)

### Bug Fixes

- Correct exit of CMUX mode ([2099434](https://github.com/espressif/esp-protocols/commit/2099434), [#103](https://github.com/espressif/esp-protocols/issues/103))
- Add filename/line info to exception message ([89e1bd2](https://github.com/espressif/esp-protocols/commit/89e1bd2))

### Updated

- Expose set_error_cb method ([ae8479c](https://github.com/espressif/esp-protocols/commit/ae8479c))


## [0.1.19](https://github.com/espressif/esp-protocols/commits/469f953)

### Features

- Add optional ACT to operator-name ([a286634](https://github.com/espressif/esp-protocols/commit/a286634), [#80](https://github.com/espressif/esp-protocols/issues/80))

### Bug Fixes

- Add missing set_pdp_context() to C-API ([4980ac8](https://github.com/espressif/esp-protocols/commit/4980ac8))

### Updated

- updated package version to 0.1.19 ([469f953](https://github.com/espressif/esp-protocols/commit/469f953))
- CI: Fix build issues ([6e4e4fa](https://github.com/espressif/esp-protocols/commit/6e4e4fa))
- esp_err_to_name (IDFGH-7793) (#78) ([d1129f3](https://github.com/espressif/esp-protocols/commit/d1129f3))


## [0.1.18](https://github.com/espressif/esp-protocols/commits/e8145fc)

### Features

- Add CMUX mode to C-API ([3fd4391](https://github.com/espressif/esp-protocols/commit/3fd4391), [#41](https://github.com/espressif/esp-protocols/issues/41))
- Add support to CMUX exit ([a16aab6](https://github.com/espressif/esp-protocols/commit/a16aab6), [#37](https://github.com/espressif/esp-protocols/issues/37))

### Bug Fixes

- Update ap2ppp example to recover network on disconnection ([a243d7e](https://github.com/espressif/esp-protocols/commit/a243d7e), [#44](https://github.com/espressif/esp-protocols/issues/44))
- Implement movable unique_buffer to bundle data, size, ptr ([66e6d4c](https://github.com/espressif/esp-protocols/commit/66e6d4c))
- DTE should own both command and data terminal ([f3ff98b](https://github.com/espressif/esp-protocols/commit/f3ff98b))
- Update CMUX example to use CMUX mode automatically ([58a0b57](https://github.com/espressif/esp-protocols/commit/58a0b57))
- Improve PPP exit sequence ([1e0aefd](https://github.com/espressif/esp-protocols/commit/1e0aefd), [#47](https://github.com/espressif/esp-protocols/issues/47))

### Updated

- Ignore format warnings ([e8145fc](https://github.com/espressif/esp-protocols/commit/e8145fc))
- Allow to customize uart source_clk ([d723fb7](https://github.com/espressif/esp-protocols/commit/d723fb7))
- Add "at" api for custom commands ([0cf08fb](https://github.com/espressif/esp-protocols/commit/0cf08fb))


## [0.1.17](https://github.com/espressif/esp-protocols/commits/5addf9e)

### Features

- Bumped version number to 0.1.17 ([5addf9e](https://github.com/espressif/esp-protocols/commit/5addf9e))

### Bug Fixes

- Support 2 byte size packets ([128c0a2](https://github.com/espressif/esp-protocols/commit/128c0a2), [#46](https://github.com/espressif/esp-protocols/issues/46))
- Correction of switching to CMUX ([503218b](https://github.com/espressif/esp-protocols/commit/503218b), [#33](https://github.com/espressif/esp-protocols/issues/33))

### Updated

- Fix param description for get_operator_name() ([a661e51](https://github.com/espressif/esp-protocols/commit/a661e51))
- Update: Removed stringstream to decrease static sizes ([3ced2d9](https://github.com/espressif/esp-protocols/commit/3ced2d9))
- Update: Renamed list_in to be type-specific Update: Removed modem-specific comment ([ba88d7f](https://github.com/espressif/esp-protocols/commit/ba88d7f))
- Update: Changed tests to coincide with new initial esp_modem mode ([4f3c429](https://github.com/espressif/esp-protocols/commit/4f3c429))
- typo ([52de8f1](https://github.com/espressif/esp-protocols/commit/52de8f1))
- Update: Removed duplicate power down function Add: gnss power mode function ([e98cf16](https://github.com/espressif/esp-protocols/commit/e98cf16))
- Update: Formatting ([be3d2ec](https://github.com/espressif/esp-protocols/commit/be3d2ec))
- Add: Sim7600 extended support ([15ed885](https://github.com/espressif/esp-protocols/commit/15ed885))
- Add: Support for SIM7000 modules ([0733ea8](https://github.com/espressif/esp-protocols/commit/0733ea8))
- Update: modem_mode::UNDEF initially ([15cbc9b](https://github.com/espressif/esp-protocols/commit/15cbc9b))
- Add: sim7070 support ([bb7f198](https://github.com/espressif/esp-protocols/commit/bb7f198))
- Add: Expanded modem_command_library with more "standard" commands ([d3f7ea6](https://github.com/espressif/esp-protocols/commit/d3f7ea6))
- Fix DCE selection in ‘pppos_client’ example ([d191a72](https://github.com/espressif/esp-protocols/commit/d191a72))
- Fix AT command in ‘set_data_mode_sim8xx()’ for SIM800 modem device ([cc0d527](https://github.com/espressif/esp-protocols/commit/cc0d527))


## [0.1.16](https://github.com/espressif/esp-protocols/commits/74040cf)

### Updated

- Extend modem_console example with USB DTE ([74040cf](https://github.com/espressif/esp-protocols/commit/74040cf))


## [0.1.15](https://github.com/espressif/esp-protocols/commits/1f5eb39)

### Updated

- Fix IDFv5.0 include paths ([1f5eb39](https://github.com/espressif/esp-protocols/commit/1f5eb39))


## [0.1.14](https://github.com/espressif/esp-protocols/commits/745201b)

### Bug Fixes

- missing default statement in a switch in the modem_console example ([325a193](https://github.com/espressif/esp-protocols/commit/325a193))
- add virtual destructors to ModuleIf and CommandableIf ([face03e](https://github.com/espressif/esp-protocols/commit/face03e))

### Updated

- build: fix issue with passing cxx_std option, a common workaround ([745201b](https://github.com/espressif/esp-protocols/commit/745201b))
- add(esp_modem): Add unit test to check polymorphic delete ([e54b240](https://github.com/espressif/esp-protocols/commit/e54b240))
- Implement esp_modem_sync for the C API ([8b3d420](https://github.com/espressif/esp-protocols/commit/8b3d420))


## [0.1.13](https://github.com/espressif/esp-protocols/commits/2cb74cf)

### Bug Fixes

- Update the test to exersise CBC parser ([d879e82](https://github.com/espressif/esp-protocols/commit/d879e82))
- Fix battery status parse ([4f1d31f](https://github.com/espressif/esp-protocols/commit/4f1d31f))
- Read module name with AT commands ([8417e23](https://github.com/espressif/esp-protocols/commit/8417e23))
- linux port to work with lwip-2.1.2 ([8465b14](https://github.com/espressif/esp-protocols/commit/8465b14))

### Updated

- Update(esp_modem): Bump component version ([2cb74cf](https://github.com/espressif/esp-protocols/commit/2cb74cf))


## [0.1.12](https://github.com/espressif/esp-protocols/commits/5d9ad9c)

### Updated

- Update FreeRTOS EventQueueHandle_t forward declaration ([5d9ad9c](https://github.com/espressif/esp-protocols/commit/5d9ad9c))


## [0.1.11](https://github.com/espressif/esp-protocols/commits/9649876)

### Updated

- New version to publish to component registry ([9649876](https://github.com/espressif/esp-protocols/commit/9649876))
- Docs: Add links to GitHub pages ([cf990d1](https://github.com/espressif/esp-protocols/commit/cf990d1))
- Add missing AT commands to plain C-API ([5299b42](https://github.com/espressif/esp-protocols/commit/5299b42))
- CI/Docs: Generate docs locally before uploading to registry ([2c21aa1](https://github.com/espressif/esp-protocols/commit/2c21aa1))
- CI/Docs: Add jobs to deploy component docs ([b9ff1e4](https://github.com/espressif/esp-protocols/commit/b9ff1e4))
- Update Task handle and Event Group handle to match freertos v10.4.3 ([5888717](https://github.com/espressif/esp-protocols/commit/5888717))
- Examples: Fix print format for http_client() API ([01e2a9c](https://github.com/espressif/esp-protocols/commit/01e2a9c))
- Examples: Fix build error when SIM needs no PIN ([c8c24ed](https://github.com/espressif/esp-protocols/commit/c8c24ed))
- Examples: Use bigger 4M flash for OTA example ([b380ded](https://github.com/espressif/esp-protocols/commit/b380ded))


## [0.1.9](https://github.com/espressif/esp-protocols/commits/2a2d270)

### Updated

- Fix CMake3.5 build with no cxx_std_17 feature ([2a2d270](https://github.com/espressif/esp-protocols/commit/2a2d270))


## [0.1.8](https://github.com/espressif/esp-protocols/commits/9dd1bd5)

### Updated

- 0.1.8: Update comonent version ([9dd1bd5](https://github.com/espressif/esp-protocols/commit/9dd1bd5))
- Add pre upload script to deploy the docs before component upload ([918db0d](https://github.com/espressif/esp-protocols/commit/918db0d))
- Minor correction of the docs ([c1b1330](https://github.com/espressif/esp-protocols/commit/c1b1330))
- Examples/console: Remove unnecessary event-base check on IP handler ([fb7295e](https://github.com/espressif/esp-protocols/commit/fb7295e))
- Examples: Extend CMux client default stack size for the main task ([8236b3d](https://github.com/espressif/esp-protocols/commit/8236b3d))
- CMUX: Refactor the protocol decoder to multiple methods per cmux state ([fb6029b](https://github.com/espressif/esp-protocols/commit/fb6029b))
- Factory: Rename Builder class to Creator, since it's not 100% builder pattern ([6e34954](https://github.com/espressif/esp-protocols/commit/6e34954))
- Formal  updates per code review ([148a930](https://github.com/espressif/esp-protocols/commit/148a930))
- Docs: Update CMux collaboration diagram to resemble composite ([1fb9150](https://github.com/espressif/esp-protocols/commit/1fb9150))
- Applied astyle code formatting ([a61e9e2](https://github.com/espressif/esp-protocols/commit/a61e9e2))
- Minor corrections per code review ([dc64f86](https://github.com/espressif/esp-protocols/commit/dc64f86))
- Bulk replace header guards to use ([3332c27](https://github.com/espressif/esp-protocols/commit/3332c27))
- Host test fix: renamed Loopback inherited member ([84b0dcf](https://github.com/espressif/esp-protocols/commit/84b0dcf))
- Update documentation and minor fixes ([e0e6585](https://github.com/espressif/esp-protocols/commit/e0e6585))


## [0.1.7](https://github.com/espressif/esp-protocols/commits/28433de)

### Updated

- Update version to 0.1.7 -- support socket VFS ([28433de](https://github.com/espressif/esp-protocols/commit/28433de))
- Reworked decouple resources from the file system ([8f17a90](https://github.com/espressif/esp-protocols/commit/8f17a90))
- Make the component compatible with IDFv4.1, v4.2, v4.3 ([69ad3ea](https://github.com/espressif/esp-protocols/commit/69ad3ea))


## [0.1.6](https://github.com/espressif/esp-protocols/commits/a67d749)

### Updated

- Bump the version and upload the component ([a67d749](https://github.com/espressif/esp-protocols/commit/a67d749))
- Updated per review comments ([ab93c13](https://github.com/espressif/esp-protocols/commit/ab93c13))


## [0.1.5](https://github.com/espressif/esp-protocols/commits/90641c8)

### Updated

- Moved to component folder ([90641c8](https://github.com/espressif/esp-protocols/commit/90641c8))
