========================================================================

1. Run ./build.sh to build the docker image based on mysql.
2. Run ./create.sh to create the container.
3. Run ./start to start the container
4. Test if the container has been fully created running ./console.sh
If the container is not ready yet the container console will not
be available. Try again.
5. Close the mysql console by entering 'exit';
6. Run ./load.sh to execute script.sql from the shared folder inside
the container and populate the database. This script also flushes
the privilages
