FROM mongo:3.7.9

COPY --from=healthcheck/mongo:latest /usr/local/bin/docker-healthcheck /usr/local/bin/

HEALTHCHECK CMD ["docker-healthcheck"]