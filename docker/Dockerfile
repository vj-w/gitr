FROM nginxinc/nginx-unprivileged:1.25.3-alpine-slim
COPY ./html /usr/share/nginx/html

ENV PRODUCTION=true

LABEL org.opencontainers.image.description="Just for fun!:)"
LABEL org.opencontainers.image.licenses="MIT"

# this is really just documentation
EXPOSE 8080