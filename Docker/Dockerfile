# Verwende das offizielle MySQL-Image als Basis
FROM mysql:latest

# Umgebungsvariable
ENV MYSQL_ROOT_USER=root
ENV MYSQL_ROOT_PASSWORD=root

# Kopiere den SQL-Code in den Container
COPY unfaelle_db.sql /docker-entrypoint-initdb.d/