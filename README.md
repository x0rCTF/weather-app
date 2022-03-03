# serverless-vpc

```
# mysql ip 
XXXXX.XXXXX.us-east-1.rds.amazonaws.com

# jumpbox ip
aws ec2 describe-instances --query "Reservations[*].Instances[*].PublicIpAddress"   --output=text
jumpbox: XXXXXXXXXXXX

# test query
INSERT INTO XXXXX.XXXX ( messageId, City, Country, Description, Temperature, Temp_min, Temp_max) VALUES ('f634b8ee-test-test-test-e27404ab0469', 'Test', 'MK', 'Sunny', 4, 2, 5);
```
