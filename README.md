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
Salesforce is your customer success platform, designed to help you sell, service, market, analyze, and connect with your customers.Salesforce has everything you need to run your business from anywhere. Using standard products and features, you can manage relationships with prospects and customers, collaborate and engage with employees and partners, and store your data securely in the cloud. 

OBJECT :
What Is an Object? 

Salesforce objects are database tables that permit you to store data that is specific to an organization. What are the types of Salesforce objects 

Salesforce objects are of two types: 

Standard Objects: Standard objects are the kind of objects that are provided by salesforce.com such as users, contracts, reports, dashboards, etc. 

Custom Objects: Custom objects are those objects that are created by users. They supply information that is unique and essential to their organization. They are the heart of any application and provide a structure for sharing data.

TABS :
What is Tab : A tab is like a user interface that is used to build records for objects and to view the records in the objects. 
Types of Tabs:
1.Custom Tabs
     Custom object tabs are the user interface for custom applications that you build in salesforce.com. They look and behave like standard salesforce.com tabs such as accounts, contacts, and opportunities.

2.Web Tabs 
     Web Tabs are custom tabs that display web content or applications embedded in the salesforce.com window. Web tabs make it easier for your users to quickly access content and applications they frequently use without leaving the salesforce.com application.

3.Visualforce Tabs
     Visualforce Tabs are custom tabs that display a Visualforce page. Visualforce tabs look and behave like standard salesforce.com tabs such as accounts, contacts, and opportunities.

4.Lightning Component Tabs
     Lightning Component tabs allow you to add Lightning components to the navigation menu in Lightning Experience and the mobile app.

5.Lightning Page Tabs
     Lightning Page Tabs let you add Lightning Pages to the mobile app navigation menu.Lightning Page tabs don't work like other custom tabs. Once created, they don't show up on the All Tabs page when you click the Plus icon that appears to the right of your current tabs. Lightning Page tabs also don't show up in the Available Tabs list when you customize the tabs for your apps.

THE LIGHTNING APP :
    An app is a collection of items that work together to serve a particular function. In Lightning Experience, Lightning apps give your users access to sets of objects, tabs, and other items all in one convenient bundle in the navigation bar.Lightning apps let you brand your apps with a custom color and logo. You can even include a utility bar and Lightning page tabs in your Lightning app. Members of your org can work more efficiently by easily switching between apps. 

Fields:
     When we talk about Salesforce, Fields represent the data stored in the columns of a relational database. It can also hold any valuable information that you require for a specific object. Hence, the overall searching, deletion, and editing of the records become simpler and quicker. 

Types of Fields 

1.Standard Fields 
2.Custom Fields 

Standard Fields: 
      As the name suggests, the Standard Fields are the predefined fields in Salesforce that perform a standard task. The main point is that you can’t simply delete a Standard Field until it is a non-required standard field. Otherwise, users have the option to delete them at any point from the application freely. Moreover, we have some fields that you will find common in every Salesforce application. They are, 
1. Created By 
2. Owner 
3. Last Modified
4. Field Made During object Creation 

Custom Fields: 
     On the other side of the coin, Custom Fields are highly flexible, and users can change them according to requirements. Moreover, each organizer or company can use them if necessary. It means you need not always include them in the records, unlike Standard fields. Hence, the final decision depends on the user, and he can add/remove Custom Fields of any given form.

PAGE LAYOUT :
Page Layout in Salesforce allows us to customize the design and organize detail and edit pages of records in Salesforce. Page layouts can be used to control the appearance of fields, related lists, and custom links on standard and custom objects' detail and edit pages.


PROFILES:
      A profile is a group/collection of settings and permissions that define what a user can do in salesforce. Profile controls “Object permissions, Field permissions, User permissions, Tab settings, App settings, Apex class access, Visualforce page access, Page layouts, Record Types, Login hours & Login IP ranges. You can define profiles by the user's job function. For example System Administrator, Developer, Sales Representative. 

Types of profiles in salesforce 

1.Standard profiles: 
       By default salesforce provides below standard profiles. 
            Contract Manager
            Read Only
            Marketing User
            Solutions Manager
            Standard User
            System Administrator.
      We cannot deleted standard ones 
Each of these standard ones includes a default set of permissions for all of the standard objects available on the platform. 

2.Custom Profiles: 
Custom ones defined by us. 
They can be deleted if there are no users assigned with that particular one.

ROLE & ROLE HIERARCHY :
        A role in Salesforce defines a user's visibility access at the record level. Roles may be used to specify the types of access that people in your Salesforce organization can have to data. Simply put, it describes what a user could see within the Salesforce organization.

UAERS : 
        A user is anyone who logs in to Salesforce. Users are employees at your company, such as sales reps, managers, and IT specialists, who need access to the company's records. Every user in Salesforce has a user account. The user account identifies the user, and the user account settings determine what features and records the user can access.

PERMISSION SETS :
        A permission set is a collection of settings and permissions that give users access to various tools and functions. Permission sets extend users’ functional access without changing their profiles and are the recommended way to manage your users’ permissions.

DASHBOARD :
        Dashboards help you visually understand changing business conditions so you can make decisions based on the real-time data you’ve gathered with reports. Use dashboards to help users identify trends, sort out quantities, and measure the impact of their activities. Before building, reading, and sharing dashboards, review these dashboard basics.
       alesforce dashboard, showcasing a visual representation of data with charts and graphs. The chart titled "range of amount per day" provides data on the rice price per kilogram across different shops. The pie chart shows different price ranges in a color-coded format, giving a quick summary of daily transactions or records related to rice sales or prices.The "All Folders" view within the Salesforce dashboard management area. It includes a folder named "amount data dashboard" with one item labeled "estimated data." This entry appears to contain data related to daily amounts, providing a summary or collection of records for easy access in the dashboard.


ABOUT APEX :
        Apex is a strongly typed, object-oriented programming language that allows developers to execute flow and transaction control statements on the Lightning platform server in conjunction with calls to the Lightning Platform? API. Using syntax that looks like Java and acts like database stored procedures, Apex enables developers to add business logic to most system events, including button clicks, related record updates, and Visualforce pages. Apex code can be initiated by Web service requests and from triggers on objects.
It is as similar as java i.e, it also supports OOP( Object oriented programming) like Classes, objects, methods.

Creating Classes :
        Apex classes are modeled on their counterparts in Java. You’ll define, instantiate, and extend classes, and you’ll work with interfaces, Apex class versions, properties, and other related class concepts.

Class:
     As in Java, you can create classes in Apex. A class is a template or blueprint from which objects are created. An object is an instance of a class.

Object:
     Object is an instance of a class, where it can access all the properties that are present in a class i.e, variables and methods.

Below metioned classes are created in the project.

ConsumerRecord Apex Class:
This class includes a sendEmailNotification method that takes a list of consumer__c records.
The method iterates over each consumer__c record in the list and creates a new SingleEmailMessage.
It sets the email's recipient, subject, and body with a personalized welcome message.
Finally, it sends the email using Messaging.sendEmail.

consumerTrigger Trigger:

This trigger is defined on the consumer__c object and is set to run after an insert operation.
It checks if the trigger is executed after an insert and then calls the sendEmailNotification method of the ConsumerRecord class, passing the newly inserted records (trigger.new).
