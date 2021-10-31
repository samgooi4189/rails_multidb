# Rails multi-db sample

### postgres db
* go do docker folder
* run `docker-compose up -d` to get the DB container up

### migrations
* rails db:migrate

### create model
`rails g scaffold Employee name:string --database secondary`
This creates Employee model using secondary DB.
