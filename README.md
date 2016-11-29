## Introduction
Manoa Kine Grindz is a reactive web-app that allows UH students to be able to quickly find what food is currently being served on campus.

## Team
<a href="https://mahoe7.github.io">Michael Hoe</a><br>
<a href="https://kpk3.github.io">Keenan Kinimaka</a><br>
<a href="https://cmakalen.github.io">Chad Makalena</a><br>

## GitHub
Milestone 1: https://github.com/manoa-kine-grindz/manoa-kine-grindz/projects/1<br>
Milestone 2: https://github.com/manoa-kine-grindz/manoa-kine-grindz/projects/2

## Installation
Clone the system over at https://github.com/manoa-kine-grindz/manoa-kine-grindz and run it on your computer using

```
meteor --settings ..config/settings.development.json
```

Deployment doesn't work right now. Sad times in the Corn Puff Kingdom.

## Usage
The landing page should look as such:

![](./images/landing1.jpg)

Click on the top right word, "Account," to log in. The system uses UH-CAS for authentication so all students and faculty within the UH system should be able to log-in without having to create an account.

![](./images/logging.jpg)
<br>
<sub style="text-align:center;">Logging in.</sub>

Once logged in, users can view and edit their profile. However, it is currently in the process of being debugged and as such it does not work right now.

![](./images/profile.jpg)
<br>
<sub style="text-align:center;">The blank page.</sub>

Also, because the databases have not yet been implemented, the Menu page is also fairly empty and the home page after logging in is still blank.

![](./images/landing2.jpg)
<br>
<sub style="text-align:center;">Home page after logging in.</sub>
<br>
![](./images/menu.jpg)
<br>
<sub style="text-align:center;">Menu page.</sub>

There is a calendar page that will be maintained by admins and will allow people to see what type of food will be served today and in the coming future. As implementing the specials is not a high priority item right now, the calendar is also blank.

![](./images/calendar.jpg)

There is a search for page that will allow the user to filter through all of the available restaurants and fast food places on campus according to ingredients and foods. This is currently a mockup.

![](./images/searchformockup.jpg)

Lastly, the Map page will show users where what food trucks are where. It will implement markers placed by the admins, but as admin privileges have not yet been implemented, it does not work. Also, the meteor package we used is outdated and does not work with the most recent build of meteor so we are currently finding a replacement.

![](./images/map.jpg)
<br>
<sub style="text-align:center;">The URL bar was included to show that there is a page for the map.</sub>

## Development
#strugglez

## Contact Us
If you have any questions, shoot us an email at mahoe7@hawaii.edu
