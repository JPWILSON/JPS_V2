# Supalist

## Overview

This was my idea for a cool startup, but I did not make a nice front end, and I think either the concept doesn't make sense, or 
I am ahead of my time lol. Read the [about](http://supalist.co/about/) page for a cheesy, cringy description, and leave some feedback via the [contact](mailto:supalist1@gmail.com?Subject=FeedbackViaGithub) section if you have the time. Thanks.

There is a psql database connected to a Flask app via sqlalchemy. 

[Here](http://supalist.co/) is what I have built, it is hosted on an AWS, EC2 instance. As you can see if you try add lists, you will need
a google account - it makes use of OAuth2. 

Recently made this, but if you are looking from your mobile, you will notice it is not exaclty the most mobile friendly front end. 
That will be my next step for improvement. Or I'll just abandon this, cause no one gets it. 

The database is initiated in database_setup.py, the initials lists made in db_population.py, and the main logic is sitting
in the um.... main.py file. 
