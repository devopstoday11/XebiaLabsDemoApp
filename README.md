# XebiaLabsDemoApp
XebiaLabs Demo App -- this is a candidate for the "Cool Apps" team's contribution to the new demo, per SE Summit Apr 2015.

**Instructions for build**

ant -DbuildNumber=n clean dar

**Instructions for deployment**

Deploy to an Environment with a Tomcat virtual host, a MySql client and a dictionary with key=DATABASE_URL and value=jdbc:mysql://localhost/test. 

To view the application, point your browser to http://yourhosturl/xlda.

