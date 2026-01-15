FROM dpage/pgadmin4:9.11

USER root

RUN apk update && apk add --no-cache \
    postgresql14-client \
    postgresql15-client \
    postgresql16-client \
    postgresql17-client

USER pgadmin
