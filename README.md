# HACKATHON car brand web scraper

A sneak peak into our HACKATHON app backend script I wrote, since it may help someone in the future 
Scrapes slovak car data from a website using a license plate number, since slovak gov doesn't provide an API for this :)


///////////////////////////////////////////////////////////////////
Takes json file as argv that might look something like this : 

{
"license plate number",
"license plate number",
"license plate number",
"license plate number"
}

///////////////////////////////////////////////////////////////////


///////////////////////////////////////////////////////////////////
And adds brand of given car if license plate is valid, or "Default" otherwise :

ex. 
{
"license plate number":"Fiat",
"license plate number:"Aston Martin",
"license plate number":"Default",
"license plate number":"Skoda"
}

///////////////////////////////////////////////////////////////////

This made for a seamless and easy car brand and adeqate brand icon assignment once a user added their car's license plate in the dashboard, which removed unnecessary clutter of having more fields to fill in when registering your car and made the UX better. 

![Alt text](preview.png?raw=true "App integration")
