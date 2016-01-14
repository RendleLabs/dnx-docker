FROM microsoft/aspnet:1.0.0-rc1-final

COPY project.json /tmp

WORKDIR /tmp

RUN dnu restore && rm /tmp/project.json /tmp/project.lock.json

WORKDIR /
