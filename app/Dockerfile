#our os
FROM alpine:3.5

# copy files required for the app to run
COPY index.html /usr/src/app/

# tell the port number the container should expose
EXPOSE 5000

# run the application
CMD ["html", "/usr/src/app/index.html"]
