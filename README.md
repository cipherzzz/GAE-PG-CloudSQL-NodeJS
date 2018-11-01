# GAE-PG-CloudSQL-NodeJS
An example of connecting a Node.js GAE application to a Cloud SQL Postgres DB 

### Start the proxy
`./start_proxy.sh`

### Open another tab and install modules
`cd cloudsql_postgresql && npm install`

### Create Google Cloud DB
Create the google cloud db and add the required parameters in
- `app.standard.yaml`
- `server.js`

### Run it
`npm start`

### Test it out
- visit localhost:8080

### Deploy it
`gcloud app deploy`
