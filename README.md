# A-CRM-APPLICATION
A CRM APPLICATION FOR WHOLESALE RICE MILL

The Rice Mill  CRM Application is a comprehensive solution designed to streamline and simplify  how much rice per day,how many were sold that rice and which type of rice all reports send to  owners daily wise. It leverages the power of customer  relationship management (CRM) to enhance customer experiences, optimize store operations, and improve overall efficiency in the rice mill factory. This project aims to develop a user-friendly and feature-rich application that addresses the specific needs of a rice mill factory.

Features and Functionality:
Reporting and Dashboards: The application can generate detailed reports and analytics regarding daily how much rice sold and total income per daily, revenue generated, popular amenities, and most buyed customers. Easy to understand the data to the owner, improving resource allocation, and planning future development.

A rollup summary field: This is a field that summarizes data from a child object to a parent object that shares a master-detail relationship. Rollup summary fields can use the COUNT, SUM, MIN, and MAX functions. For example, you could use a rollup summary field to display the total value (amount of rice supplied ) from rice  details on a related supplier.

A cross-object formula field: It  is a formula field that references fields from another object in Salesforce. This type of formula allows users to calculate the total amount from number of rice taken*price/kg  and it displays the total amount I have to pay.

Validation rules: validation rules  also include an error message to display to the user when the rule returns a value of “True” due to an invalid value.so , In this project i gave Isblank formula.Isblank formula is used to verify whether it is blank it shows error.

Permission sets: Organization Wide Defaults(OWD) in salesforce is the baseline level of access that the most restricted user should have. Organizational Wide Defaults are used to restrict access.But in our case we created roles and given the roles in such a way that the owner  can see   employer  and worker  records , and the employer can see the worker  records.

Introduction to Salesforce
Introduction:
Are you new to Salesforce? Not sure exactly what it is, or how to use it? Don’t know where you should start on your learning journey? If you’ve answered yes to any of these questions, then you’re in the right place. This module is for you. 

Welcome to Salesforce! Salesforce is game-changing technology, with a host of productivity-boosting features, that will help you sell smarter and faster. As you work toward your badge for this module, we’ll take you through these features and answer the question, “What is Salesforce, anyway?”.

What Is Salesforce? 
Salesforce is your customer success platform, designed to help you sell, service, market, analyze, and connect with your customers. 

Salesforce has everything you need to run your business from anywhere. Using standard products and features, you can manage relationships with prospects and customers, collaborate and engage with employees and partners, and store your data securely in the cloud. 

ABOUT APEX :
ConsumerRecord Apex Class:

This class includes a sendEmailNotification method that takes a list of consumer__c records.
The method iterates over each consumer__c record in the list and creates a new SingleEmailMessage.
It sets the email's recipient, subject, and body with a personalized welcome message.
Finally, it sends the email using Messaging.sendEmail.

consumerTrigger Trigger:

This trigger is defined on the consumer__c object and is set to run after an insert operation.
It checks if the trigger is executed after an insert and then calls the sendEmailNotification method of the ConsumerRecord class, passing the newly inserted records (trigger.new).


ABOUT DASHBOARD :

Salesforce dashboard, showcasing a visual representation of data with charts and graphs. The chart titled "range of amount per day" provides data on the rice price per kilogram across different shops. The pie chart shows different price ranges in a color-coded format, giving a quick summary of daily transactions or records related to rice sales or prices.

The "All Folders" view within the Salesforce dashboard management area. It includes a folder named "amount data dashboard" with one item labeled "estimated data." This entry appears to contain data related to daily amounts, providing a summary or collection of records for easy access in the dashboard.

