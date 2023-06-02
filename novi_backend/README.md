**CAR SHOP**

Prerequisite:
_install GoLang locally_

To start backend open terminal/cmd prompt and position yourself into the main bcknd folder. Then type go run cmd/carshop/main.go

This is a simple CRUD backend service with mocked data, that wraps simple operations including:

2. Create operation (add car)
3. Read operation (retrieve 1 car from given ID)
4. List operation (retrieve X cars)
7. Delete operation (soft-delete 1 row from database, from given ID)

Also, this service offers authentication services:

1. Log the user in (create token)
2. Log the user out (destroy token)
