#our os
FROM alpine:3.5
#apache 
FROM httpd:2.4


# copy files required for the app to run

 COPY index.html /usr/local/apache2/htdocs/
 COPY node_modules /usr/local/apache2/htdocs/
 COPY fav.png /usr/local/apache2/htdocs/
 COPY logo.png /usr/local/apache2/htdocs/
 COPY styles.css /usr/local/apache2/htdocs/

# tell the port number the container should expose
EXPOSE 5000

