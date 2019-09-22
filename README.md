# Milestone Project 1
### Description
---
The following project is my first Milestone project in the "Full stack Developer" course at Code Institute. My goal is to create a responsive, mobile first approch website, using what we learned so far in HTML and CSS. We are allowed to use framework and other prewritten CSS codes, such as Bootstrap and font Awesome if we documented it. We got different scopes to choose from our we could choose one of our own and my first Milestone I choose one of my own. The website does not include a back-end functionality, so the forms on the site is not active and will thus not send any infomation.

The project is about a "nearly" local salmon river named Etne. In the summer season I spend a lot of my time fishing for salmons and I wanted to create an eye-catching website that is easy to navigate wherever you using a mobile, table or a desktop. The website would serve as a place where the users can get the latest news from the river, see the latest catches and more.


Link to the project: <a href="https://weekend79.github.io/salmon/index.html">Click here</a>

### UX
---
I wanted to ensure that the website had easy access to the most important infomation so on my landing page the users will find the following; links to water levels and live cam behind the fishtrap, as well as booking and the login form. While navigating the navbar will direct you to other information such as general information and history about the river, latest catches, contact information, picture gallery and a separet login section. For my index page I have chosen a cover picture at the top so the site below scroll above the images to make a cool effect for the user. In the cover photo you will find the header with the navbar as well as the header and login form. The login form is a bootstrap form that I have formed the way i wanted using CSS. Below the cover photo I have used the classes of Rounded-circle in Bootstrap to have a circle frame around my images. Abvove the footer you will find the 3 latest news from admin, to set this up I have used Bootstrap's "spacing-section". 

The "about LaksiEtne" are showing "Lorem Ipsum" content today, but this will later be where the user will find content about the histroy as well as general information about the river Etne. For this I have used the Bootstrap Grid System to set the spacing between the content and I have a header and an intro text about the river and to the right you will find an images of the river. Below you will find 2 colums and 2 row that displays "Lorem Ipsum" content. You will also find the same news section that you can see on the index page. 

The salmonsuite - catches page you will find the latest 10 catches, 10 biggest catches and for screen sizes above 1200px will also see 3 different charts. The charts are Google scripts and shows the percentage of how much salmon vs seabass and other species, the comparison between the different species over the years as well as the percentage between the different baits that the salmon have been hooked on. The table used to display the latest catches as well as the biggest catches are Bootstrap code and have been costumized in CSS.  

The Rules page consist of an images at the top that have been centered using Bootstrap. Below you will find the rules for fishing in the river. 

The Picture Gallery displaying 7 different images from the river, later it will be possible to see the photos uploaded by the user, but for now it's only the images that admin wants to display that you will see in the picture gallery. For the gallery I have used Bootstrap's Carousel for displaying the images. The images will change by it self or you can choose to navigate thru the images using the buttons on the left and right for the images. 

For both the contact page and login page I have used Bootstrap forms and costumized it CSS. Beside the forms you will find the contact information on the contact page. 

Below are images of my wireframes that I create during my 5 planes some have been altered so I have later changed this to how it looks today, so the displayed images is what you can expect to find on the site today. 

<img src="https://i.imgur.com/pJlSoC9.png" alt="LaksiEtne.no" width="750">

### Features
---
#### Current Features
---
```sh
* Index - A place where users will find links to third party sites. As well as booking and login.
* About Laksietne - A place where the users can learn more about the river and its history.
* Salmonsuite/catches - Here users will find information related to catches, together with 3 charts 
  displaying information about the different species, baits and a comparison of the latest 10 years. 
* Salmonsuite/rules - Here the users will find information about the rules for fishing in the river. 
* Picture Gallery - Here the users will find a picture gallery 
* Contact Us - this page the users will find a contact form as well as the contact information. 
* Login page - A login form
```

#### Future features
---
```sh
* Both Norwegian and English languages.
* An app where the users can upload images of their catches and a log to register their catches 
directly in the app.  
* A login section where the users can do much of the same as in the app. But they will also be allowed
to comment on each others picture and follow each other. 
* Update all content
```

### Technologies / Support Used
---
Below is a list of technologies I've used to build my website
* HTML - HTML5 Provided the content and the structure of my website. 
* CSS - CSS were used to style my site. 
* [Bootstrap](https://getbootstrap.com/) - I've used Bootstrap for framework, forms, section-spacing and the picture carousel.
* [AWS Cloud9](https://aws.amazon.com/cloud9/) I've used AWS Cloud9 as my text editor. It offer everything I need to do from one enviroment. 
* [Git](https://git-scm.com) - Git was used for version control and pushing the code to GitHub
* [GitHub](https://github.com/) - This is where my repository is held externally.
* [Javascript/JQuery](https://jquery.com/) - This was imported via the Bootstrap framework to enable me to create a responsive collapsible nav bar at smaller screen sizes.
* [Google Fonts](https://fonts.google.com/) - Used to import specific fonts I wanted to use on my website.
* [Google Scripts](https://developers.google.com/chart/) - Used to add charts in the Salmonsuite/catches page.
* [Font Awesome](https://fontawesome.com/) - I used Font Awesome for the icons in my navbar and the buttons on my index page. .
* [Imgur](https://imgur.com/) - I used Imgur to store my picture's that I've used on my site. 


### Testing
---
I have tested the site both manually and automatically throughout the development of the project. I've used the web developer tools to see that my site at all time was responsive. I target first the mobile devices, and then testing to scale the site for tablets to larger desktops. I tested the site on different devices to see that it scaled properly on all devices. 
The automatic checks of my HTML and CSS structure were done in [W3C Validator](https://validator.w3.org/#validate_by_input) to ensure there isn't any errors in the code and that the structure is correct. I have tested the site on Firefox, Internet explorer and Chrome to see that the site scales properly, as well as all features and framework is correct in it's positions. Everything scales properly on all devices beside the Google scrips when the Internet Explorer is used in the Salmonsuite/Catches page, here the scripts don't show and you can read more about this in the bugs section futher down in the README.md file.   

### Bugs
---
During the testing of my build I discovered that the Google script wasn't scaling properly on screen sizes below 1200px, so I choose to hide the scripts for medium screen sizes and below. A better knowledge about script will help me scale the charts properly so it will be visible on all devices. 
The images used on the site is stored with [Imgur](https://imgur.com/) since I had some problems with the link to the images and they just didn't want to show. 

### Deployment
---
My website was created using AWS Cloud9. AWS Cloud9 is the text editor that have some free credits that follow the course material. The AWS account has an buildt in Terminal and this was used to push my code to GitHub.
After the development of the navbar I pushed the code with all pages to GitHub and could follow the lifespan of my development. 

* In the bash terminal use "git init"
* Created all my folder and files.
* Use "git add ." into the bash terminal
* Use "git commit" into the bash terminal and create "initial commit"
* Link your local git repository to a GitHub repository.
* Follow the below steps to deply the site to GitHub pages. 
 
##### To deploy the website to GitHub pages follow the below steps:
* Select the "salmon" from my GitHub dashboard.
* Select "Settings" from the menu bar. 
* From the GitHub pages section, I chose "master branch" from the dropdown menu. 
* Once selected, the page refreshes and a link will be displayed in the GitHub section to my website.
* Link to the project: <a href="https://weekend79.github.io/salmon/index.html">Click here</a>

### To run this project locally
---
* Follow this link to the [GitHub Repositiry](https://github.com/weekend79/salmon)
* Click on the 'Clone or Download' button.
* Copy the URL provided.
* Open a bash terminal, move to your desired directory.
* Type 'git clone' and paste in the URL.

### Contributing
---
* To my mentor [Reuben Ferrante](https://github.com/arex18), for giving my exellent guidens thru the project and assisted me in some important issue's.
* [Jamie Boyd](https://github.com/jboyd8) for having a great README.md file that I learned a lot from. 
* [HTML Color Code](https://www.htmlcolor-picker.com/color/) - Used this website in order to obtain hex codes to styling my pages.
* [W3C Validator](https://validator.w3.org/#validate_by_input) - A validator used to check my HTML and CSS structure and format periodically throughout the build.
* [W3Schools](https://www.w3schools.com/) - I used this to ensure I was entering all the information required correctly in my HTML and CSS.

### Author

* **Morten Viken** - *Initial work* - [weekend79](https//github.com/weekend79)

