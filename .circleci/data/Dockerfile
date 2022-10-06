FROM bitnami/magento:2
MAINTAINER Open Source Team

WORKDIR /opt/bitnami/magento
COPY auth.json /opt/bitnami/magento
RUN composer config minimum-stability dev
RUN composer require pagarme/pagarme-magento2-module:dev-test

