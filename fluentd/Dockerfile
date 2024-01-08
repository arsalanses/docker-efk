ARG FLUENTD_VERSION
ARG ES_PLUGIN_VERSION

FROM fluent/fluentd:${FLUENTD_VERSION}

USER root

RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", ${ES_PLUGIN_VERSION}]

USER fluent
