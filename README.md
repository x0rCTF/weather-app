# serverless-vpc

```
# mysql ip 
masterdb.cqnfhoewhffm.us-east-1.rds.amazonaws.com

# jumpbox ip
aws ec2 describe-instances --query "Reservations[*].Instances[*].PublicIpAddress"   --output=text
jumpbox: 54.221.160.130

# test query
INSERT INTO mentorship.WeatherApp ( messageId, City, Country, Description, Temperature, Temp_min, Temp_max) VALUES ('f634b8ee-test-test-test-e27404ab0469', 'Test', 'MK', 'Sunny', 4, 2, 5);
```
