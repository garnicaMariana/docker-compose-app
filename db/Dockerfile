FROM mysql:5.7

ENV MYSQL_DATABASE=LPURLS
ENV MYSQL_USER=lpurlsuser
ENV MYSQL_PASSWORD=lpurlspasswd
ENV MYSQL_ROOT_USER=root
ENV MYSQL_ROOT_PASSWORD=lpurlspasswd

ADD mydb.sql /docker-entrypoint-initdb.d
EXPOSE 3306
