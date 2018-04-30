# ubuntu-ssh-postgresql
Docker image of Ubuntu that contains the Postgresql database and that can be accessed through SSH.

# USAGE
docker run -d -p 22:22/tcp javi98/ubuntu-ssh-postgresql

# USER AND PASSWORD
user:     usuario

password: 12345678

# PROBLEM DOES NOT CONNECT POSTGRESQL
service postgresql start
