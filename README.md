# NSWI152 - Vývoj cloudových aplikací

_Michal Pácal_

Toto je můj proof-of-work pro předmět NSWI152, část Azure Services.

## Lab 1

- Publikoval jsem aplikaci: [01.png](Lab1-AppServicesDeployment/01.png)
- Ověřil jsem dostupnost: [02.png](Lab1-AppServicesDeployment/02.png)

## Lab 2

- Založil jsem SQL service: [01-SQL_service.png](Lab2-AzureSQL/01-SQL_service.png)
- Vytvořil tabulku příkazem: [02-SQL_setup.png](Lab2-AzureSQL/02-SQL_setup.png)
- Publikoval jsem a spustil aplikaci: [03-WebJob.png](Lab2-AzureSQL/03-WebJob.png)

## Lab 3

- Založil jsem storage container: [01-storage.png](Lab3-AzureBlobStorage/01-storage.png)
- Nahrál jsem do něj soubor
- Přistoupil jsem na něj pomocí aplikace: [02-website.png](Lab3-AzureBlobStorage/02-website.png)

## Lab 4

- Založil jsem Cosmos databázi: [01-db.png](Lab4-AzureCosmosDB/01-db.png)
- Použil jsem demo aplikaci se základníma operacema: [02-demo-app.png](Lab4-AzureCosmosDB/02-demo-app.png)

## Lab 5

- Založil jsem Insights
- Připojil jsem aplikaci: [02-Insights-connection.png](Lab5-ApplicationInsights/02-Insights-connection.png)
- Použil jsem aplikaci
- Zkontroloval jsem report: [01-Insights-overview.png](Lab5-ApplicationInsights/01-Insights-overview.png)

## Lab 6

- Přidal jsem právo aplikaci přistupovat na storage: [01-role-assignment.png](Lab6-AzureKeyVault/01-role-assignment.png)
- Založil jsem keyvault
- Přidal jsem práva aplikaci: [02-keyvault-permissions.png](Lab6-AzureKeyVault/02-keyvault-permissions.png)
- Použil jsem ukázkovou aplikaci pro přístup do vaultu: [03-keyvault-app.png](Lab6-AzureKeyVault/03-keyvault-app.png)
- Použil jsem webovou aplikaci pro přístup do storage a vaultu: [04-webapp.png](Lab6-AzureKeyVault/04-webapp.png)

## Lab 7

### 7a

- Založil jsem EventHub
- Použil jsem ukázkové aplikace: [a1-message.png](Lab7-Serverless/a1-message.png)
- Zkontroloval jsem využití hubu: [a2-stats.png](Lab7-Serverless/a2-stats.png)

### 7b

- Zprovoznil jsem funkci lokálně: [b1-local-run.png](Lab7-Serverless/b1-local-run.png)
- Založil jsem Function App
- Funkci jsem publikoval: [b2-deployment.png](Lab7-Serverless/b2-deployment.png)
- Použil jsem publikovanou funkci: [b3-deployed-run.png](Lab7-Serverless/b3-deployed-run.png)
- Zkontroloval jsem využití: [b4-deployed-metrics.png](Lab7-Serverless/b4-deployed-metrics.png)

### 7c

- Založil jsem Logic App
- Vytvořil jsem workflow (místo Gmail komponenty jsem použil Outlook pro odesílání emailu)
- Použil jsem aplikaci z 7a pro poslání zprávy do EventHubu
- Zkontroloval jsem, že workflow proběhl: [c1-workflow-run.png](Lab7-Serverless/c1-workflow-run.png)
- Dostal jsem email: [c2-email.png](Lab7-Serverless/c2-email.png)

## Lab 8

### 8a

- Použitý obrázek: [a-sample-image.jpg](Lab8-CognitiveServices/a-sample-image.jpg)
- Založil jsem Computer Vision: [a1-compvision-created.png](Lab8-CognitiveServices/a1-compvision-created.png)
- Použil jsem aplikaci: [a2-example-app.png](Lab8-CognitiveServices/a2-example-app.png)
- Použil jsem konzoli: [a3-example-console.png](Lab8-CognitiveServices/a3-example-console.png)
- Použil jsem studio: [a4-example-studio.png](Lab8-CognitiveServices/a4-example-studio.png)

### 8b

- Použitý obrázek: [b-sample-image.jpg](Lab8-CognitiveServices/b-sample-image.jpg)
- Použil jsem aplikaci: [b1-ocr.png](Lab8-CognitiveServices/b1-ocr.png)

### 8c

- Použil jsem svoji fotku
- Založil jsem Face API: [c1-face-created.png](Lab8-CognitiveServices/c1-face-created.png)
- Použil jsem aplikaci: [c2-app.png](Lab8-CognitiveServices/c2-app.png)

### 8d

- Založil jsem Speech service: [d1-speech-created.png](Lab8-CognitiveServices/d1-speech-created.png)
- Nahrál jsem svůj hlas (pomocí Audacity)
- Použil jsem Speech studio: [d2-studio.png](Lab8-CognitiveServices/d2-studio.png)
