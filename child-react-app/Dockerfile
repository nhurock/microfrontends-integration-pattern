FROM httpd:alpine
LABEL Child React App - Microfrontend example
MAINTAINER Dario <pizzuto.dario@alice.it>

# Remove any files that may be in the public htdocs directory already.
RUN rm -r /usr/local/apache2/htdocs/*

# Copy all the files from the docker build context into the public htdocs of the apache container.
COPY ./dist /usr/local/apache2/htdocs/