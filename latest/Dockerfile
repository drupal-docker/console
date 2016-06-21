FROM drupaldocker/php:cli
MAINTAINER drupal-docker <info@drupaldocker.org>

RUN composer global require drupal/console:@dev \
 && ln -s ~/.composer/vendor/bin/drupal /usr/local/bin/drupal

ENTRYPOINT ["drupal"]

CMD ["list"]
