## Overview 

Career Match provides a new way for connecting companies with a matching system. Students can select their skills to match with companies or browse companies with zip-code to find out geographic preference. The recruiter also can explore students’ profiles with the interest and skills that the company is looking for. The site can match students to employers and vice-versa.

Students who visit the site can create a profile with their interests (skills), preferred geographic location by zip-code, and link to their professional portfolio page. Admins can monitor the site for inappropriate content, and create new categories for the students and recruiters.
New user goes to landing page, logs in, gets home page, sets up profile.
Admin goes to landing page, logs in, gets home page, edits site.
User goes to landing page, logs in, finds companies with compatible interests, contacts them.
Recruiter goes to landing page, logs in, add company to Career Match, explore student’s profile.

The Github Organization for this project can be found [here](https://github.com/career-match/)

## Deployment

The latest version of the app is hosted [here](https://career-match.connectiveunconscious.com)

## User Guide

### Landing page
The landing page is the first page presented to the user. Helps with vistor to understand the features of the site.

<img src="doc/landingMockup.png">
<img src="doc/landingMockup3.PNG">

### Student home page
The student home page is the page presented to the user who logged in as a student.

<img src="doc/studentpage.png">

### Company home page
The company home page is the page presented to the user who logged in as a recruiter.

<img src="doc/companyhomepage.png">

### Admin home page
The admin home page is the page for the admin.

### Student profile page
The student profile page is a page presented to the user with list of the profiles of students.

<img src="doc/studentprofilepage.png">

### Company profile page
The company profile page is a page presented to the user with a list of the profiles of the company with descriptions.

<img src="doc/companyprofilepage.png">

### Browse companies and users by skill, geographic preference
The page where users can search the companies by skills and geographic preference.

<img src="doc/searchpage.png">

<!-- ## Community Feedback -->

## Developer Guide

To build Career Match locally, first clone the career-match repository to your system:  
```git clone https://github.com/career-match/career-match.git```

Career Match uses [Meteor](https://www.meteor.com) which can be installed using npm with the command:  
```npm install -g meteor```

Install the dependencies using (while in the `career-match/app` folder):  
```meteor npm install```

Build the app locally with:  
```meteor npm run start```

To use the locally built app, connect using a web browser to `http://localhost:3000`.

The app is designed to be deployed using [Meteor Up](http://meteor-up.com), which will have to be configured for the particular webserver you wish to host it on.

## Development History

[Milestone 1](https://github.com/career-match/career-match/projects/1) (complete)

[Milestone 2](https://github.com/career-match/career-match/projects/2)

## Approach
Instead of sending out announcements each year, a company can create a page in the site that lists:  

- A brief overview of the company.
- Geographic location of the company.
- A list of positions that they commonly recruit for from new UH graduates. Each position has a brief description, a set of skills, whether it’s an internship, permanent position, or both, how many people they would like to hire, and salary range.
- Links to pages for additional information.
- Contact email(s) for followup.

Students who visit the site can create a profile with their interests (skills), preferred geographic location, and link to their professional portfolio page.  

Admins can monitor the site for inappropriate content, and create new categories of musical tastes, capabilities, and goals.  

## Contact Us
Career Match was designed and implemented by:
- [Cathy Kim](https://github.com/cathy-kim95)
- [Gerald Lee](https://github.com/glee25)
- [Ian Eshelman](https://github.com/IanEshelman)
- [Jay Ramos](https://github.com/ramosJay)
- [Stephanie Aelmore](https://github.com/believeinlain)
