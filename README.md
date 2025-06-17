# Vecka 35 : AWS IAM Bootcamp

## IAM Basics

1. Skapa en IAM User med namnet “Batman” och alla rättigheter för EC2

2. Skapa en till IAM User med namnet “Robin” och alla rättigheter för Lambda

3. Lägg båda IAM Users i en IAM grupp som heter “batcave”

4. Tilldela IAM gruppen “batcave” rättigheter att hantera roller ( IAM )

5. Skapa en IAM User som heter” Alfred” och har rättigheter till både Lambda och EC2

6. Skapa en IAM Role som litar på Lambda och får läsa ur en DynamoDb databas

7. Skapa en IAM Role som litar på Lambda och som får läsa och skriva i en DynamoDb databas samt hantera allt om EventBridge

## Policys - Mer än Basic

8. Skapa en IAM Policy med namnet “DynamoDb reader” som tillåter läsrättigheter i DynamoDBs samtliga tabeller

9. Skapa en IAM Policy med namnet “DynamoDb writer” som tillåter skrivrättigheter i DynamoDBs tabell orders

10. Skapa en IAM Policy med namnet “EC2handler” som tillåter alla actions i samtliga EC2 instanser

11. Skapa en IAM Policy med namnet “noScans” som tillåter alla actions förutom “scan” i samtliga DynamoDb-tabeller.

12. Skapa en IAM Policy som tillåter alla actions i samtliga Lambdas samt läsrättigheter i samtliga DynamoDb-tabeller

13. Skapa en till IAM Role med namnet “LambdaHandler” och applicera ovanstående policy

14. Skapa en till IAM Group med namnet “Admins” och applicera Aws managed policy 
AdministratorAccess. Lägg till en policy som tar bort rättigheterna till EC2 från gruppen.
