ARG FLUENTD_VERSION

FROM fluent/fluentd:${FLUENTD_VERSION}

USER root

# RUN gem uninstall -I elasticsearch
# RUN gem install elasticsearch -v 8.11.0

RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-document", "--version", "5.4.2"]

USER fluent
