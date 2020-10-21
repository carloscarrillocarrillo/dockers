docker build -t awsdocker .


```
docker run --name awsdocker --rm -i -t awsdocker bash
```

````
docker tag awsdocker carloscarrillo/aws-docker
````

````
docker push carloscarrillo/aws-docker
````
