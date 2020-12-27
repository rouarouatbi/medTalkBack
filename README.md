# medTalkBack
This is the backend of our application which is made with spring boot to ensure the safety of our doctors.

The content is as follows:
config package => mainly for security
controller package
dto package
exceptions package
mapper package
model package 
repository package
security package
and service package

To activate this application you need to change the application properties also create a user in mailTrap.io and put your credentials in this api ensures the enabling of the user by sending you an email where you get to verify your account. we used the api mailTrap for its simplicity in providing a fake SMTP server that would allow us to safely and rapidly test our application.

you will also need to provide a database. you only need to create spring-reddit-clone schema and the rest of the tables will be automatically created.

We used JPA and hibernate to create our tables and spring web security to provide the security needed. we also made sure to make a refresh token.

All you need to do now is to run the application and enjoy :) !
PS: make sure to read the other readME!!
