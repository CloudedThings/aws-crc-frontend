steps done so far:
1. create DynamoDb table
2. create Lambda function to update visits attribute in the table
3. create an API with Lambda integration to get the clicks into the table
4. create a S3 hosted static website
5. create a CNAME record for Lightsail hosted zone
6. Host website with the CNAME record
7. Include a script that will make calls to API and get the value from table (visitors counter). Activate CORS, allow calls only form website.
8. Set-up GitHub Actions for front end (created a new IAM Role for that)


**TODO**:
* fix the index.html, css and js 
