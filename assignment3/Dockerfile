FROM 6789012345/myjdk-alpine:latest
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . /usr/src/app/
RUN chmod 755 /usr/src/app/
ENTRYPOINT ["sh", "system-capabilities.sh"]