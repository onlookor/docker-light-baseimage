# Changelog

# 0.1.0
  - Change NAME as "onlookor/..." and VERSION as "0.1.0" in Makefile.
  - Change locale to zh_CN in build.sh.
  - Change the baseimage tag to "latest" in Dockerfile.
  - Add zoneinfo file "Shanghai" and link it to /etc/localtime.
  - Change LANG, LANGUAGE, LC_ALL enviroment to "zh_CN.UTF-8" in Dockerfile.
  - Include locale path zh* in dpkg_nolocales.
