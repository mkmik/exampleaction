FROM bitnami/minideb

LABEL "name"="sh"
LABEL "maintainer"="Marko Mikulicic <mkm+actions@bitnami.com>"
LABEL "version"="1.0.0"

LABEL "com.github.actions.name"="Example action"
LABEL "com.github.actions.description"="Does something"
LABEL "com.github.actions.icon"="terminal"
LABEL "com.github.actions.color"="gray-dark"

COPY entrypoint.sh /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]