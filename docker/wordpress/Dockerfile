ARG WP_IMAGE='wordpress:latest'
FROM ${WP_IMAGE}

# Include custom build code
RUN apt-get update -y \
      && apt-get install -y \
         libxml2-dev \
      && apt-get clean -y
RUN docker-php-ext-install soap