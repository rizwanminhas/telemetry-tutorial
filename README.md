A very simple app that demos Opentelemetry and Zipkin.

# How to run?

1. Start zipkin
```
docker run -d -p 9411:9411 --name zipkin openzipkin/zipkin 

```
2. Install dependencies
```
npm install
```
3. Run the app
```
node app.js
```
4. Make some requests to the app
```
curl http://localhost:8080
```
5. Visit the zipkin ui in the browser
```
http://localhost:9411/zipkin
```