
# Nemid PP Network Connection Test

Test network connectivity to the Nemid PP (pre production) environment.


## Debian or Ubuntu Linux

```
sudo apt-get install ldap-utils
./ldapsearch-test.sh
```

## Docker

#### Build the docker image
```
docker build -t docker-nemid-pp-connection-test .
```

#### Test Network Connection
```
docker run -it docker-nemid-pp-connection-test
```
