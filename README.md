RESTFul Basic Authentication - Service Build
--------------------------------------------

Securing Restful Web Services with Basic Authentication - OAuth 1.0 using Username/Password
<br/><br/><br/>
The flow of application will go something like this:<br/><br/>
===============================================================
<br/>
1. Download/Clone the application in to your machine.<br/>
2. Unzip the application in to a directory.<br/>
3. Open the IDE - Eclipse/Intellij/RAD/Net Beans and import the project using <b>"Existing Maven Projects".</b> <br/>
4. Resolve all errors by importing jars, setting build path, JRE and Maven dependencies. <br/>
5. Clean the project and deploy on tomcat (web) server. <br/>


<br/><br/><br/>
URL:<br/>
====
<br/>
http://<hostname>:<port>/WebServicesBasicAuth/user/list <br/>
Authentication: Username/Password
<br/>
<b>Note:</b> Either you can use the url in REST Client application (Postman/Chrome REST Client/Insomnia) or hit the url directly in browser <br/>
If you want to provide authentication as header, provide as below <br/>
Authentication: Basic<space><Base64 Endode value in format "username:password">
















