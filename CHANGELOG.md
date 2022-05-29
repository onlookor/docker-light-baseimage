# Changelog

## [0.1.0] - 2022-05-29
### Changed
  - Change NAME as "onlookor/..." and VERSION as "0.1.0" in Makefile.
  - Change locale to zh_CN in build.sh
  - Change the baseimage from buster-slim to bullseye-slim in Dockerfile
  - Change LANG, LANGUAGE, LC_ALL enviroment to "zh_CN.UTF-8" in Dockerfile
  - Set TZ as "Asia/Shanghai" in Dockerfile
  - Include locale path zh* in dpkg_nolocales
