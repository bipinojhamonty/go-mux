# go-mux

# To run postgrace db use this command
docker run --name some-postgres -p 5432:5432 -e POSTGRES_PASSWORD=mysecretpassword -d postgres

# Export these 3 variables
export APP_DB_USERNAME=postgres

export APP_DB_PASSWORD=mysecretpassword

export APP_DB_NAME=postgres

# the source refered from 
https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql
