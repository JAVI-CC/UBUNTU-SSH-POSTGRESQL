# ubuntu-ssh-postgresql
Docker imagen de Ubuntu que contiene la base de datos Postgresql y que se puede acceder mediante SSH.

# USAGE
docker run -d -p 22:22/tcp javi98/ubuntu-ssh-postgresql

# USER AND PASSWORD
user:     usuario
password: 12345678

# PROBLEM DOES NOT CONNECT POSTGRESQL
service postgresql start
