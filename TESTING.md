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
The warning was ignored followiing design decsions. 

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

* The site to be laid out in a way that is easy to navigate, so that I can find what I need. 

* The site to be responsive and navigable for various device sizes; desktop, tablet, and phone. For the content to look good on all of the devices.

* To learn more about the site owner.

* To be able to view the site owners educational background, to ensure they are qualified for the job.

* To be able to view the site owners previous job experience. 

* To be able to download the site owners cv, to share and keep for future use. 

* To be able to see previous projects completed, as well as read a short description about the project.

* To be able to connect to the site owners social media accounts. 

* To be able to easily get in contact with the site owner via a contact form.

## Bugs

* The comments inside the HTML files were all written with CSS comment format, this was discovered when runniing the HTML code through the validator. 
  * This was solved by using the correct HTML comment. format. 

* "The element a must not appear as a descendant of the button element" was the error message recieved when running the HTML code through the valiidator. 
  * The buttons were changed to a tags with an href inside them and styled accordingly. 

* The screen size for iPhone 5/SE was not responsive. 
  * This was solved by adding in a media query with a min-width of 320px and max-width of 568px. All content was then styled accordingly. 