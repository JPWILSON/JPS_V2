# Supalist

## Overview

This was my idea for a cool startup, but I did not make a nice front end, and I think either the concept doesn't make sense, or 
I am ahead of my time lol. 

It is a web application with a psql database connected to a Flask app via sqlalchemy. 

[Here](http://supalist.co/) here it is live, it is hosted on an AWS, EC2 instance. As you can see if you try add lists, you will need
a google account - it makes use of OAuth2. Read the [about](http://supalist.co/about/) page for a cheesy, cringy description, and leave some feedback [contact](mailto:supalist1@gmail.com?Subject=FeedbackViaGithub) if you have the time to take a look. Thanks.

It is a recent demo project, but if you are looking from your mobile, you will notice it is not exactly the most mobile friendly front end. 
That will be my next step for improvement. Or I'll just abandon this, cause no one gets what I thought it could be. 

The database is initiated in database_setup.py, the initials lists made in db_population.py, and the main logic is sitting
in the um.... main.py file. 
