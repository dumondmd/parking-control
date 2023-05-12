

# Spring Boot

### Desenvolvimento de API



## GET

http://localhost:8080/

```json
Funcionando!
```


## GET - ALL

http://localhost:8080/parking-spot

```json
[
  {
    "id": "8f732e33-6aea-4017-8cb3-7eb2f3288a1e",
    "parkingSpotNumber": "216B",
    "licensePlateCar": "ARS872",
    "brandCar": "audi",
    "modelCar": "q5",
    "colorCar": "black",
    "registrationDate": "2023-05-12T21:31:22Z",
    "responsibleName": "Diogox",
    "apartment": "217",
    "block": "A"
  },

  {
    "id": "6800f4bd-ef23-4f02-8e42-f3615071b7d1",
    "parkingSpotNumber": "206B",
    "licensePlateCar": "RRS871",
    "brandCar": "audi",
    "modelCar": "q20",
    "colorCar": "black",
    "registrationDate": "2023-05-08T21:57:40Z",
    "responsibleName": "Diogox",
    "apartment": "215",
    "block": "A"
  }
]
```

## GET - ID

http://localhost:8080/parking-spot/6800f4bd-ef23-4f02-8e42-f3615071b7d1

```json
{
    "id": "6800f4bd-ef23-4f02-8e42-f3615071b7d1",
    "parkingSpotNumber": "206B",
    "licensePlateCar": "RRS871",
    "brandCar": "audi",
    "modelCar": "q5",
    "colorCar": "black",
    "registrationDate": "2023-05-08T21:57:40.400898",
    "responsibleName": "Diogox",
    "apartment": "215",
    "block": "A"
}
```


## POST

http://localhost:8080/parking-spot

```json
{
  "parkingSpotNumber": "276B",
  "licensePlateCar": "ARS875",
  "brandCar": "audi",
  "modelCar": "q5",
  "colorCar": "black",
  "responsibleName": "Diogox",
  "apartment": "257",
  "block": "A"
}
```

```json
{
    "id": "886f7d58-4261-480b-a6a0-c53b63740078",
    "parkingSpotNumber": "276B",
    "licensePlateCar": "ARS875",
    "brandCar": "audi",
    "modelCar": "q5",
    "colorCar": "black",
    "registrationDate": "2023-05-12T22:34:33.060653",
    "responsibleName": "Diogox",
    "apartment": "257",
    "block": "A"
}
```


## PUT

http://localhost:8080/parking-spot/6800f4bd-ef23-4f02-8e42-f3615071b7d1

```json
{
    "parkingSpotNumber": "206B",
    "licensePlateCar": "RRS871",
    "brandCar": "audi",
    "modelCar": "q20",
    "colorCar": "black",
    "responsibleName": "Diogox",
    "apartment": "215",
    "block": "A"
}
```

```json
{
    "id": "6800f4bd-ef23-4f02-8e42-f3615071b7d1",
    "parkingSpotNumber": "206B",
    "licensePlateCar": "RRS871",
    "brandCar": "audi",
    "modelCar": "q20",
    "colorCar": "black",
    "registrationDate": "2023-05-08T21:57:40.400898",
    "responsibleName": "Diogox",
    "apartment": "215",
    "block": "A"
}
```

## DEL


http://localhost:8080/parking-spot/886f7d58-4261-480b-a6a0-c53b63740078

```json
Estacionamento deletado!
```
