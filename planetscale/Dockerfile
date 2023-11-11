FROM cloudmix/planetscale-local:latest

ENV MYSQL_URL mysql://maria:pass@db:3306/animal

ENV PORT 8080

ENV WAIT_VERSION 2.7.2

ADD https://github.com/ufoscout/docker-compose-wait/releases/download/$WAIT_VERSION/wait /wait

RUN chmod +x /wait

CMD ""