```bash
curl http://localhost:8080/
```

```bash
curl -H "Content-Type: application/json" -X POST -d '{
    "firstName": "Bruno",
    "lastName": "Diaz"
}'  http://localhost:8080/
```


```bash
curl -X DELETE http://localhost:8080/1
```

```bash
curl -H "Content-Type: application/json" -X PUT -d '{
    "id": 6,
    "firstName": "Bruno",
    "lastName": "Diaz Rodriguez"
}'  http://localhost:8080/6
```
