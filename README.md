# Courses SQLite Database
Courses Database is a SQLlite database for Courses demo page witch gives back JSON object. Each course is represented as a separate object, containing several attributes.

### **Link to the API:** https://river-spice-blouse.glitch.me/courses

### Endpoints

`GET [/courses]` - gets all the courses\
`GET [/courses/:id]` - gets one course based on id


## Atributes
`id [number]` - A unique identifier for the course\
`category [string]` - The course category\
`name [string]` - The course name\
`img [string]` - The path to the course thumbnail\
`description [string]` - A brief overview of the course content\
`address [string]` - Name of the street and number\
`city [string]` - Name of the city where course take a place\
`capacity [number]` - The capacity for the course