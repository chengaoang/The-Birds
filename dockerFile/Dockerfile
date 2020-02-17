FROM busybox
LABEL maintainer="1981907427@qq.com" app="angryBird"

ENV ROOT="/angrybird/"
RUN mkdir -p $ROOT && cd $ROOT && wget ~ && unzip *.zip
#echo "<h1>Hello busyboxHttpdServer</h1>" > ${WEB_ROOT}/index.html
CMD /bin/httpd -f -h ${ROOT}

