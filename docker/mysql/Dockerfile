FROM mysql/mysql-server:8.0
LABEL maintainer="littleheroes <support@littleheroes.jp>"

ARG DOCKERDIR

COPY ${DOCKERDIR}/mysql/my.conf /etc/my.conf
RUN chmod 644 /etc/my.cnf