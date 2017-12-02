FROM postgres:9.6.5

MAINTAINER Daniel Nogueira <danielnogueira.dev@gmail.com>

#-----------------------------------------------------------------------------------------------#
# Ajusta a configuração do PostgreSQL para ser possível fazer conexão remota ao banco de dados. #
#-----------------------------------------------------------------------------------------------#
RUN echo "host all  all    0.0.0.0/0  md5" >> /var/lib/postgresql/data/pg_hba.conf

CMD ["postgres"]

EXPOSE 5432