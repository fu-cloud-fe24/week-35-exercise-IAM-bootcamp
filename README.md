# Vecka 35 : AWS IAM Bootcamp

## IAM Basics

1. Skapa en IAM User med namnet “Batman” och alla rättigheter för EC2

2. Skapa en till IAM User med namnet “Robin” och alla rättigheter för Lambda

3. Lägg båda IAM Users i en IAM grupp som heter “batcave”

4. Tilldela IAM gruppen “batcave” rättigheter att hantera roller ( IAM )

5. Skapa en IAM User som heter” Alfred” och har rättigheter till både Lambda och EC2

6. Skapa en IAM Role som litar på Lambda och får läsa ur en DynamoDb databas

7. Skapa en IAM Role som litar på Lambda och som får läsa och skriva i en DynamoDb databas samt hantera allt om EventBridge
