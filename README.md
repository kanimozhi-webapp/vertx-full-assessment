# Vert.x Backend Assessment – Kanimozhi

## How to Build
```
mvn clean package
```

##  How to Run
```
mvn exec:java -Dexec.mainClass=com.example.Launcher
```

## How to Run Tests
```
mvn test
```

## Endpoint
POST `http://localhost:8080/v1/points/quote`

### Body:
```json
{
  "fareAmount": 100,
  "currency": "USD",
  "promoCode": "SUMMER25"
}

