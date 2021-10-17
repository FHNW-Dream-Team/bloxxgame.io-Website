# The different stages of this Dockerfile are meant to be built into separate images
# https://docs.docker.com/develop/develop-images/multistage-build/#stop-at-a-specific-build-stage
# https://docs.docker.com/compose/compose-file/#target

# -----------------------------------------------------------------------------
# Build
# -----------------------------------------------------------------------------
FROM composer:2 as vendor

COPY composer.json composer.json
COPY composer.lock composer.lock

RUN composer install --ignore-platform-reqs --no-interaction --prefer-dist

# -----------------------------------------------------------------------------
# PHP base
# -----------------------------------------------------------------------------
FROM craftcms/nginx:8.0-dev

COPY --chown=www-data:www-data --from=vendor /app/vendor/ /app/vendor/
COPY --chown=www-data:www-data . .
