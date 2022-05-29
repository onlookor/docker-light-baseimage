FROM debian:bullseye-slim

COPY . /container
RUN /container/build.sh

ENV LANG="zh_CN.UTF-8" \
    LANGUAGE="zh_CN:zh" \
    LC_ALL="zh_CN.UTF-8" \
    TZ="Asia/Shanghai"

ENTRYPOINT ["/container/tool/run"]
