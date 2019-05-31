# SlackDevForDevOps
For test something devops flow with slack

## Usage
1. cd docker/
2. docker-compose up -d
3. open browser , input url "localhost"

---

# About Lambda_get_logs code
- Develope with cloudwatch auto send alarm notification to slack channel , and use CloudWatch -> SNS -> lambda function to make it !

1. This code is put on aws lambda function to cache cloudwatch alarm data
2. Pipe cloudwatch alarm data to get in alarm status [instance id , metric name]
3. Intergation slack notification 

---
# Add two config file name `config` and `credentials` ---> do no upload your credentials to internet  
* config - for develope invoke aws resources
* credentials - for develope invoke aws resources

