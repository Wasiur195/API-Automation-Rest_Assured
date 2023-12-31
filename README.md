# API-Automation-Rest_Assured
API-Automation-Rest_Assured-SDET-Batch6
Here, the following tasks are done:
- Login Feature Tested Using Proper Validation, Negative Test Cases Added For Email.
- Can Create Customer and agent Accounts by Name, Email, Phone number, Password, Nid and Role, Proper Validation, and Secret Key Token. Both Positive And Negative Test Cases are Added For it.
- Can Search Any Customer by Proper ID.
- Can Deposit Money to the Agent Account From the System..
- Can Check Customer & Agent Account Balance.
- Can Cash into the Customer account Through the Agent Account.
- Can Cash Out From Customer Account.
- Can Send Money To Another Customer Account.
- The Variables are Set and Used From "config.properties" File.<br><br>

### Technology: </br>
- Tool: REST Assured
- IDE: IntelliJ
- Build tool: Gradle
- Language: Java
- Framework: TestNG<br><br>

### Prerequisites</br>
- Install JDK 8 or any LTS version
- Configure JAVA_HOME and GRADLE_HOME
- Download Allure 2.18.1 and configure environment path
- Stable internet connection

### Project Run
- Clone the repo [API-Automation-with-Rest-Assured_TestNG](https://github.com/ahnafahmad/Dmoney-Trnx-API-Automation-Rest_Assured.git)
- Open cmd in the root folder.
#### Run the Automation Script by the following command:
 ```
 gradle clean test 
 ```
 
 - Give the following commands by opening the terminal in the project folder to create an Allure Report:
```
Allure generate allure-results --clean -o allure-report
 ```
 ```
 Allure serve allure-results
```


## Rest Assured TestNG API Automation Allure Report Image


![1](https://user-images.githubusercontent.com/58990500/204823153-6c01bcb5-f097-4f6e-9cf2-02a494bcbec0.PNG)



![2](https://user-images.githubusercontent.com/58990500/204823205-8113d907-fbc4-4bc3-9aeb-9900349729ef.PNG)



![3](https://user-images.githubusercontent.com/58990500/204823251-7d14f744-b2ce-4056-a660-c2c8bf03bbcd.PNG)


