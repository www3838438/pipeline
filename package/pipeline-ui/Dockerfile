FROM nginx:1.12
ENV UI_VERSION 1.0.1
ADD https://www.github.com/rancher/pipeline-ui/releases/download/v${UI_VERSION}/${UI_VERSION}.tar.gz /dist.tar.gz
RUN tar -xzf /dist.tar.gz && mv /${UI_VERSION}/* /usr/share/nginx/html/
EXPOSE 80