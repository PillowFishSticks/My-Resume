# Testing 

## Code validators 

[HTML validator](https://validator.w3.org/)

* Home Page

![index validator](/readme-files/index-validator.png)

* Resume Page

![resume validator](/readme-files/resume-validator.png)

* Project Page

![Project validator](/readme-files/project-validator.png)

* Contact Page

![Contact validator](/readme-files/contact-validator.png)

Notes:
The warning was ignored following design decisions. 

[CSS validator](https://jigsaw.w3.org/css-validator/validator)

![css validator](/readme-files/css-validator.png)

## Responsiveness

[Chrome DevTools](https://developer.chrome.com/docs/devtools/) was used to test the responsiveness of the site. 

![Devices](/readme-files/devices.png)
![Responsiveness](/readme-files/responsiveness.png)

## Browser compatibility 

![Browser compatibility](/readme-files/browser-compatibility.png)

## Testing User stories 

* To be able to easily find the information I am looking for, the layout needs to make sense so that I am not put off. 
    * The navbar offers easy navigation for the user and is clearly labeled. 
    * The website is easy to navigate with all content labeled clearly indicating its purpose. 


* The site to be laid out in a way that is easy to navigate, so that I can find what I need. 
    * The navbar offers easy navigation for the user and is clearly labeled.  

* The site to be responsive and navigable for various device sizes; desktop, tablet, and phone. For the content to look good on all of the devices.
    * The user can load the website on mobile, tablet, and desktop devices. 

* To learn more about the site owner.
    * The user can find out more about the site owner on the **Home Page**.
    * The user can download the site owners cv on the **Resume Page** at the bottom via the Download CV button. 


* To be able to view the site owners educational background, to ensure they are qualified for the job.
    * The user can find educational background on the **Resume Page** under Education. 
    * Alternatively, the user can download the site owners cv on the **Resume Page** at the bottom via the Download CV button. 

* To be able to view the site owners previous job experience. 
    * The user can find previous job experience on the **Resume Page** under Experience. 
    * Alternatively, the user can download the site owners cv on the **Resume Page** at the bottom via the Download CV button. 

* To be able to download the site owners cv, to share and keep for future use. 
    * The user can download the site owners cv on the **Resume Page** at the bottom via the Download CV button. 
    * Once downloaded, the user is free to keep and share the CV. 

* To be able to see previous projects completed, as well as read a short description about the project.
    * The user can find a short description of each project on the **Project Page**. 
    * The user can also view the projects' website and repository via the buttons under each project. 

* To be able to connect to the site owners social media accounts. 
    * The user can find links to the site owners social media accounts at the bottom of each page.   

* To be able to easily get in contact with the site owner via a contact form.
    * The user can use the contact form on the **Contact Page** to get in touch with the site owner. 
    * Alternatively, the user can contact the site owner via the email or telephone number provided at the bottom of each page. 

## Bugs

* The comments inside the HTML files were all written with CSS comment format, this was discovered when running the HTML code through the validator. 
    * This was solved by using the correct HTML comment format. 

* "The element a must not appear as a descendant of the button element" was the error message recieved when running the HTML code through the valiidator. 
    * The buttons were changed to a tags with an href inside them and styled accordingly. 

* The screen size for iPhone 5/SE was not responsive. 
    * This was solved by adding in a media query with a min-width of 320px and max-width of 568px. All content was then styled accordingly. 

* The navbar was not fixed after applyng the class top-nav.
    * This was solved by adding the fixed-top class to the nav element. 

* The hamburger icon and drop down menu were not displaying. 
    * This was solved by removing Bootstap 5 and using Bootstrap 4.6.0 instead. 

* The Project Page for mobile view was showing skewed margins for each paragraph of text. 
    * This was solved by using Chrome DevTools which highlighted a div missing a closing bracket, which was then added. 

Go back to [README.md](https://github.com/PillowFishSticks/My-Resume/blob/master/README.md)