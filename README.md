# keypair.yaml
AWSTemplateFormatVersion: '2010-09-09'
Description: Create a keypair value 
Resources:
  Batch11keypair:
    Type: AWS::EC2::KeyPair
    Properties: 
      KeyName: nareshkey
      KeyType: rsa
      Tags: 
        - Key: "Name"
          Value: "nareshkey"
