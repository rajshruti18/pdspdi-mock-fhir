# pdspdi-mock-fhir

### run

```
docker-compose -f docker-compose.yml -f volume/docker-compose.yml up --build
```

### test
```
docker-compose -f docker-compose.yml -f volume/docker-compose.yml -f test/docker-compose.yml up --build -V --exit-code-from pds-mock-fhir-test
```
### test hapi-fhir
```
### test
```
docker-compose -f docker-compose.top.yml -f volume/docker-compose.yml -f test/hapi-fhir/docker-compose.yml up --build -V --exit-code-from pds-mock-fhir-test-hapi-fhir
```

