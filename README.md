# Postman Basics

Postman is one of the most popular software testing tools which is used for API testing. With the help of this tool, developers can easily create, test, share, and document APIs.


# Introduction to Postman
- Postman is a standalone software testing API (Application Programming Interface) platform to build, test, design, modify, and document APIs. It is a simple Graphic User Interface for sending and viewing HTTP requests and responses.

- While using Postman, for testing purposes, one doesn't need to write any HTTP client network code. Instead, we build test suites called collections and let Postman interact with the API.

- In this tool, nearly any functionality that any developer may need is embedded. This tool has the ability to make various types of HTTP requests like GET, POST, PUT, PATCH, and convert the API to code for languages like JavaScript and Python.



# Terms Used in Postman 
- API
Application Programming Interface (API) is software that acts as an intermediary for two apps to communicate with each other. We use APIs whenever we use an application like Twitter, Facebook, sending text messages, or checking the weather over the phone.


<image src="api-restaurant-analogy-example.jpg" alt= "Analogy">


- HTTP
HTTP (Hypertext Transfer Protocol) is the collection of rules for the transmission of data on the World Wide Web, like graphic images, text, video, sound, and other multimedia data. The Web users implicitly make use of HTTP as soon as they open their Web browser.

Example: A user or browser enters the HTTP request to the server; the server then returns the user response. This response includes the request status information and may consist of the requested material as well.

The most commonly used HTTP methods are GET, POST, PUT, PATCH, HEAD, DELETE, and OPTIONS.



# Postman Install
=> Steps to download and install the native Postman application -

- Step-1: Go to the link https://www.postman.com/downloads/ and click download based on your operating system.

<image src="instal-update.png" alt="install">

- Step-2: For downloading the app for Windows, click on the download button and select the particular version. 

- Step-3: Check the download progress on the bottom left if using the Chrome browser. Once the .exe file is downloaded, install the application.

- Step-4: Once the installation completes, it redirected to a window as shown in the image below where it can be clicked for Stop signing in and take straight to the app (as this app can also be used without logging in) otherwise a new window opens up to sign up.

 <image src="postman-install.png" alt="window">

- Step-5: Create your account

- Step-6: After signing in, select the workspace tools as per your requirement, and then click on, continue to get the startup screen.

You're all set!!


# API Testing and Unit Testing 

Unit testing is done by the Developers or by Test Engineers and is done on a class by class basis or on the single component level. A major emphasis is on the fact whether each unit or module works perfectly fine in isolation. 

API testing is basically black box testing which is simply concerned with the final output of the system under test. 
API testing primarily aims to test the business logic layer of the system's architecture. API testing is primarily handled by the QA team, which requires them to run any API on top of a particular build meant to serve a specific purpose.

API testing also tests the unit as part of a system, while unit testing typically tests the unit in relative isolation from the rest of the system. 

<image src="Unit Testing Vs API.png" alt="Unit Vs API">


# Postman UI Terms 

<image src="navigation.png" alt="navigation">

- Request

It is used to create a new request, where you can create and save requests by entering the request name and can use it in the future.

- Collection

It saves your requests in the form of a collection for reusing and sharing.

- Environment

Environments are variables with key-values. Every variable name represents its key. So if we reference the name of the variable, it enables us to access its corresponding value. So it basically saves the values you frequently use in an environment.

- Documentation - to create documentation for API.

- Mock server- to create in-development APIs.

- Monitor- to test API performance.

- API - for managing all aspects of APIs, including design, development, and testing.

<image src="API.png" alt="API">

- Import - the Import option for importing files in different formats into the software.

- Runner - helps to directly run the loaded collections in the Postman.

- Open new icon - used to open a new Tab, a new Postman window, and a new Runner window.

<image src="sidenavbar.png" alt="navbar">

- My Workspace - helps you to view, manage, and create personal as well as team workspaces. Collections, monitors, environments, and mocks are components of the workspace.

- Sync icon - used to synchronize the API requests that we send from other devices and updates your postman account status.

- Interceptor icon - It is a proxy server, used to capture all the requests that send through browser or phone or from any other device.

- History - It automatically keeps a record of all API requests, just like any other browser. It keeps handy all your past searches.

- Collections - It is the group of related requests which are displayed under the collection tab. We can also create a new collection. A Trash section from where you can recover your lost or deleted collections.

- APIs - All the APIs are listed in this section. New API can also be created from this tab.

- Untitled Request - It is basically the default request title you are working on. The title depends on the type of request method.

- HTTP request - It opens a drop-down list of all the HTTP request methods, like GET, DELETE, PATCH, OPTIONS, LINK, POST, COPY, UNLOCK, PURGE, etc. Widdely used POST and GET.

- Request URL or Endpoint - It is like any other browser URL. Here, we mention the link to where the API will communicate with.

- Params - It is used to write the parameters of the request. These parameters include key values and descriptions.

- Authorization - It is required to access the APIs. This process verifies whether we have permission from the server to access the data we want. 

- Headers - An HTTP request header is the additional data that is required to send along with the request. This header information is required for proper two-direction communication between the client and the server.

- Body - It specify the data type that need to send with a request. There are various types of body data that can be sent to match your API.

- Pre-request script - These are written in JavaScript, and executed before sending the request. Generally, these scripts are for setting the environment and ensuring that the request is running in the right environment.

- Test scripts - It is executed during the request. It is also written in JavaScript. This helps to ensure that API works as intended. Testing is important as it sets up checkpoints to verify whether the response status is ok and retrieved data is as expected.

- Response - The API responses which are sent back from the server are shown in the response window. These are generated after sending an API request to the server. 



# Sending First Request

Sending a request is as easy as posting a URL into your web browser.
An API request helps you to access, or send, data from a data source.

To send the API request, we need an HTTP method. Some commonly used methods are POST, GET, DELETE, PUT, and PATCH.

GET: This HTTP method is used to access the data from an API.

POST: This method transmits new data.

DELETE: This is used to remove or delete the existing data.

PATCH: This method is used to update the existing data.

PUT: This method is used to update the existing data.

Without any terminal or code, we can make API requests and review the answers with the help of postman. 
Just build a new request and select the send button, you'll get the API response.