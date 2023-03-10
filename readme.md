## Servita Onboarding 01

### Setup project
1. Initialise a node.js project using npm or yarn
2. Install your favourite HTTP server library with npm or yarn
3. Setup an application that listens on port 8080 for incoming HTTP requests
4. Create a GET route to handle requests when localhost:8080/aggregate is opened in the browser.
5. In the handler for the GET route, implement the below

### Aggregate Data
1. Asynchronously get the data from `GET https://directory.spineservices.nhs.uk/STU3/Organization/N81082`
2. We want to loop through the extensions and build the object below:

```javascript
{
    maxStart: Date,
    minStart: Date,
    valueCodings: {
        "key": value
    }    
} 
```

3. Follow further instructions from interviewer
