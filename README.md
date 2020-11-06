Docker compose script to get postgres:13 and pgadmin 4 running locally.
I added a 0 to the end of the default ports in case you already have non-containerized versions of this software running.
All marked values should probably be changed to suit.
@see https://linuxhint.com/postgresql_docker/

To start, run `docker-compose up -d`
To stop, run `docker-compose down`
To flush either postgres or pgadmin data, simply remove the volumes
