FROM node:16-alpine

LABEL version="0.1.0"
LABEL repository="http://github.com/cesium/actions"
LABEL homepage="http://github.com/cesium/actions/cli"
LABEL maintainer="CeSIUM"
LABEL "com.github.actions.name"="Netlify CLI"
LABEL "com.github.actions.description"="Wraps the Netlify CLI to enable common Netlify commands"
LABEL "com.github.actions.icon"="cloud"
LABEL "com.github.actions.color"="blue"

RUN npm install -g netlify-cli

COPY entrypoint.sh /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]