# XebiaLabsDemoApp
XebiaLabs Demo App -- this is a candidate for the "Cool Apps" team's contribution to the new demo, per SE Summit Apr 2015.
Instructions for Deployment:
Package as an ordinary WAR file and deploy to Tomcat.

Database configuration on MySQL is default port and test database.

create table registration (id bigint, name varchar(25), email varchar(30), phone_number varchar(12)); 
alter table registration add primary key (id);      
alter table registration modify column id bigint auto_increment;         

Then, create user=xebialabs, password=xebialabs and grant privileges on this table.
