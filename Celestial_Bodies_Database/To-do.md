# Celectial Bodies Database Project

## Database
* [ ] Db = "universe"
* [ ] Connect to DB

## Tables
* [ ] Galaxy
* [ ] Star
* [ ] Planet
* [ ] Moon
* [ ] +1
* [ ] + 3 rows

## Columns
* [ ] Primary Key (name = table_name_id)
    * [ ] Auto Increment
* [ ] Name (VARCHAR)
* [ ] Non FK && Int
* [ ] Non FK && Int
* [ ] Numeric
* [ ] Text
* [ ] Boolean
* [ ] Boolean
* [ ] Not NULL
* [ ] Not NULL
* [ ] UNIQUE

## References
* [x] Star -> Galaxy
* [ ] Planet => Star
* [ ] Moon => Planet

## Notes: 
* Create dump:  ```pg_dump -cC --inserts -U freecodecamp universe > universe.sql ```
* Rebuild DB: ```psql -U postgres < universe.sql```