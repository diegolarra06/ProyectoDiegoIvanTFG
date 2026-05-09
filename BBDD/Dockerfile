FROM mysql:8.4

ENV MYSQL_DATABASE=adopta_un_companero

COPY ["BaseDeDatosAdoptaUnCompañero.sql", "/docker-entrypoint-initdb.d/01_init.sql"]

CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_unicode_ci"]