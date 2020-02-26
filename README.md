# ExportBlockchain-Steps
Steps for setting up Export Blockchain in Bluemix tesing environment  
[Click on this link to use bluemix](https://composer-playground.mybluemix.net/login)

## Step 1
Deploy a new business network using the test-export-v1(2).bna file provided in the repository

## Step 2
Create partipants such as Exporter,Bank,ExportOfficer and DGFTofficer using the admin network card

### Exporter Participant
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/Create%20Exporter%20.png "Exporter participant")
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/Exporter%20created%20.png "Exporter participant")

### Bank Participant
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/create%20Bank%20entity.png "Bank participant")
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/Bank%20created.png "Bank participant")

### ExportOfficer participant
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/create%20Export%20Officer%20.png "ExportOfficer participant")
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/export%20officer%20created%20.png "ExportOfficer participant")

### DGFTofficer participant 
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/create%20dgft%20.png "DGFT participant")
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/dfgt%20officer%20created%20.png "DGFT participant")

## Step 3
Issue identities to all participants 

### Go to ID registry
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/Goto%20ID%20registry.png "Goto ID registry")

### Issue an ID as shown below for exporter
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/create%20exporter%20ID.png "Issue ID")

### Repeat the same for other paticipants 

### The ID registry should look like this 
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/ID%20registry.png "ID registry")

### The Business Network dashboard should look like this 
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/Issued%20IDs.png "Business Network Dashboard")

## Step 4
Submit transactions through different patricipant IDs

### use the Export Officer Card to create the asset SHB by using the createSHB transaction
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/create%20SHB.png "create SHB")
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/SHB%20Asset%20created.png "SHB created")

### use the Bank Card to upadte the status of the asset SHB by using the updateSHB_byBank transaction
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/update%20SHB%20by%20bank.png "update SHB")
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/SHB%20status%20realised.png "SHB updated")

### use the DGFT Officer Card to upadte the status of the asset SHB by using te updateSHB_byDGFT transaction
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/issue%20incentive%20by%20dgft.png "update SHB")
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/SHB%20status%20utilized.png "SHB updated")

## Step 5

### Use the All transactons option to view the Transaction History
![alt text](https://github.com/MarvinTellis/ExportBlockchain-Steps/blob/master/Transaction%20History.png "Transaction History") 
