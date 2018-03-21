# spring-httpstatus-javascript
[org.springframework.http.HttpStatus](https://docs.spring.io/spring-framework/docs/current/javadoc-api/org/springframework/http/HttpStatus.html) enum implementation for frontend.
## Installation ##
```console
npm install spring-httpstatus-javascript --save
```
## Usage ##
```javascript
import HttpStatus from 'spring-httpstatus-javascript'

/* Comparison */
response.status == HttpStatus.OK

/* Get message of status*/
HttpStatus.getStatusText(HttpStatus.OK)
```

