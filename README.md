# Timestamp-Microservice
Public repo to complete "Timestamp Microservice" exercise on freeCodeCamp

# Tests
- <ins>Passed</ins>: You should provide your own project, not the example URL.
- <ins>Passed</ins>: A request to /api/:date? with a valid date should return a JSON object with a unix key that is a Unix timestamp of the input date in milliseconds (as type Number)
- <ins>Passed</ins>: A request to /api/:date? with a valid date should return a JSON object with a utc key that is a string of the input date in the format: Thu, 01 Jan 1970 00:00:00 GMT
- <ins>Passed</ins>: A request to /api/1451001600000 should return { unix: 1451001600000, utc: "Fri, 25 Dec 2015 00:00:00 GMT" }
- <ins>Passed</ins>: Your project can handle dates that can be successfully parsed by new Date(date_string)
- <ins>Passed</ins>: If the input date string is invalid, the API returns an object having the structure { error : "Invalid Date" }
- <ins>Passed</ins>: An empty date parameter should return the current time in a JSON object with a unix key
- <ins>Passed</ins>: An empty date parameter should return the current time in a JSON object with a utc key

# Public display 

https://timestamp-microservice.simobonvalot.repl.co/
