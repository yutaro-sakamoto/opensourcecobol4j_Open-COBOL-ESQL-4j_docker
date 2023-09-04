# The development environment for opensource COBOL 4J and Open COBOL ESQL 4J

This is 

In order to launch the development environment, run the following command.
```bash
docker compose up -d
docker attach oc4j_client
```

Run the following in the docker container and execute sample programs of Open COBOL ESQL 4J
```bash
cd /root/ocesql4j_sample
make
```
