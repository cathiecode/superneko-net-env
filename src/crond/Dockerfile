FROM ghcr.io/cathiecode/docker-cron:latest

RUN apk add certbot rclone certbot-nginx nginx postgresql15

COPY ./src/certbot-renew /certbot-renew
