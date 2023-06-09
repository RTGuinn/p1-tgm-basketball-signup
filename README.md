# TGM Basketball Clinic

TGM Basketball Clinic is a place for children ages 12 and up to join and work on their basketball skills and physical fitness that will be useful when playing basketball.  This site will target parents or guardians who have children that play basketball and want every opportunity to improve upon their skills.  This site will give the opportunity for parents or guardians to sign up their children for a time and location to be at to join in on the skills clinic.
View the live site [here](https://rtguinn.github.io/p1-tgm-basketball-signup/)

![site on different screen sizes computer laptop tablet and iphone](docs/readme_images/responsive.png)




# Features

## Navigation Bar

        Shown on all 3 pages, A fully responsive navigation bar including links to the Logo, Home page, Gallery and Sign Up page.  Navigation bar is the same on each page for easy navigation.

        This will allow any user to easily navigate throughout the site on any device without having to use the "back" button.

![navigation buttons for home gallery and sign up](docs/readme_images/navbar.png)

## Main Page Image

        The Main page includes a picture of the clinics adtertisement model and some text for the user to sign up their children.
        This section introduces the user to TGM Basketball Clinic with a photo that catches their attention.

![main logo and description of clinic with sign up option](docs/readme_images/homepage.png)

## About TGM Clinics

        TGM Basketball Clinics are 1 hour sessions designed to help your child work on and improve their basketball skills under the direct supervision of a seasoned veteran professional.
        While in the clinic the children will be evaluated throughout the session and given individual instruction on how and what they need to do and work on so as to be the best they can be.
        At the end of each session the kids will join together to have a fun challenge of a basketball game called shoot-out or stress to end each session with some fun.

![text that explains what clinic is about](docs/readme_images/aboutus.png)

## Gym Times and Locations

        The times and locations section allows the user to see when the clinics are happeing, where they will be located and for how long they will last.
        
![times and locations for each clinic](docs/readme_images/times.png)

## Footer section

        The footer section has social links to the TGM Clinic media sites.  The links will open in new tabs so as to allow easy navigation for the user.
        The social links encourage the users to keep in contact and connected through the media sites

![two images for facebook and instagram links](docs/readme_images/footer.png)

## Gallery

        The Gallery shows images of previous TGM Clinics for the user to look at and see what the clinics involve and are about.
        This section lets the user see some of the activities their kids will take part in.

![images of kids in previous clinics](docs/readme_images/gallery.png)

## Sign Up

        This Sign Up section is a form that allows the user to sign up their kids and afterwards get a thank you message to let them know they have signed up successfully.

![form with name and email areas to fill in](docs/readme_images/signup.png)

## Thank you page

        This page lets the user know they have successfully signed up for the basketball clinic and also has a link back to the home page.

![thank you message after signing up with clickable link to go back](docs/readme_images/thankyou.png)

## 404 error page

        This page lets the user know the input they have typed in is not correct and has a link to take them back to the previous page.

![error page with clickable link to go back](docs/readme_images/404.png)

## Existing Features
- Responsive design
- Responsive gallery page
- Sign up form and thank you message

## Future features to be done
- Table of contents to be added with links to each section of readme.md
- An updated sign up form with background image

# Design
## Wireframe

## Home Page

![wireframe image of how home page should look](docs/wireframe_images/home.png)
![wireframe image of how home page should look on phone](docs/wireframe_images/phonehome.png)

## Gallery Page

![wireframe image of how gallery page should look](docs/wireframe_images/gallery.png)
![wireframe image of how gallery should look on phone](docs/wireframe_images/phonegallery.png)

## Sign up Page

![wireframe image of how sign up page should look](docs/wireframe_images/signup.png)
![wireframe image of how sign up page should look on phone](docs/wireframe_images/phonesignup.png)

## Thank you page

![wireframe image of how thank you page should look](docs/wireframe_images/thankyoupg.png)
![wireframe image of how thank you page should look on phone](docs/wireframe_images/phonethankyou.png)

## 404 Page not found

![wireframe image of how 404 error page should look](docs/wireframe_images/404error.png)
![wireframe image of how 404 error page should look on phone](docs/wireframe_images/phone404.png)





# Technologies

- HTML
    - The structure of the website was developed using HTML as the main language

- CSS
    - The website was styled using custom CSS in an external file

- Codeanywhere
    - The website was developed using Codeanywhere IDE

- Github
    - Source code is hosted on GitHub and deployed with Git pages

- Git
    - Used to commit and push code during the development of the website

- Font Awesome
    - Icons from https://fontawesome.com/ were used for the social media links in footer

- Resize Pixel
    - Images were resized using https://www.resizepixel.com/ for gallery section

- Favicon.io
    - Favicon files were created with https://favicon.io/favicon-generator/ 

- Balsamiq
    - Wireframes were created using https://balsamiq.com/wireframes/

# Testing

## Responsiveness

All pages were tested to make sure responsiveness on different screen sizes functioned and worked properly on Chrome, Safari and Windows.

- Steps to test:

    1. Open browser and navigate to https://rtguinn.github.io/p1-tgm-basketball-signup/
    2. Open developer tools (right click and inspect)
    3. Set to responsive and decrease to 600px
    4. Click and drag responsive window to max width

- Expected:
Website responds on all screen sized and no images are pixelated or stretched and no elements overlap.

- Actual:
Website acted as it should and no problems were found.

Website was also opened on iphone 13 plus with no problems.

## Accessibility

Wave Accessibility tool was used at the end of developing the website for final testing of the deployed website to check for any aid accessibility testing.

Testing was to ensure the following criteria were met:
- All pages have aria-labels and associated labels so it is read out on a screen reader.
- Color contrasts meet a minimum ratio
- Heading levels are not missing or skipped to ensure the importance of content is correctly outputted to the user.
- Everything is contained within landmarks to ensure ease of use for assistive technology.
- All images has alternative text and titles so it is read out on screen readers.

On Wave Accessibility there was an problem that came up.
- Problem: Nearby images using some of the same alternativve text.

- Solution: I could not figure another way to fix this problem as images are closely related to each other and an alternative explanation for each image would not work.


## Lighthouse Testing

![image of test result for home page from lighthouse](docs/readme_images/lighthouse_testhome.png)
![image of test result for gallery page from lighthouse](docs/readme_images/lighthouse_testgallery.png)
![image of test result for sign up page from lighthouse](docs/readme_images/lighthouse_testsignup.png)

## Functional Testing

Navigation Links
- Testing was performed to make sure all navigation links go to the page they are supposed to when clicked on.
This test was done by clicking on each link on each page.

| Navigation Link | Page to Load |
|-----------------|--------------|
| Home | index.html |
| Gallery | gallery.html |
| Sign up | signup.html  |

All links on all pages navigated to the correct page as expected.

## Form Testing

The form on the sign up page was tested to make sure its functionality worked as expected when names and emails were input correctly and incorrectly.   The following test scenarios were covered:

- Scenario One - Correct Inputs
Steps to test:
    1. Go to Sign up page from home page
    2. Input following data into form:
        - First Name: John
        - Last Name: Smith
        - Email: John_Smith@test.com
    3. Click Sign Up button
    4. User is redirected to thankyou.html for confirmation that they signed up.

Expected:

Form submits with no errors and user is redirected to thankyou.html confirmation page with clickable link to go back to home page.

Actual:

Website behaved as expected with no errors and redirected to thankyou.html.

- Scenario Two - Missing Required First Name field
Steps to test:
    1. Go to Sign up page from home page
    2. Input following data into form:
        - First Name: 
        - Last Name: Smith
        - Email: John_Smith@test.com
    3. Click Sign Up button

Expected:

Form does not submit and shows required First Name to be filled in.

Actual:

Website behaved as expected and showed required First Name to be filled in.

- Scenario Three - Missing Required Last Name field
Steps to test:
    1. Go to Sign up page from home page
    2. Input following data into form:
        - First Name: John
        - Last Name:
        - Email: John_Smith@test.com
    3. Click Sign Up button

Expected:

Form does not submit and shows required Last Name to be filled in.

Actual:

Website behaved as expected and showed required Email to be filled in.

- Scenario Four - Missing Required Email field
Steps to test:
    1. Go to Sign up page from home page
    2. Input following data into form:
        - First Name: John
        - Last Name: Smith
        - Email: 
    3. Click Sign Up button

Expected:

Form does not submit and shows required Email to be filled in.

Actual:

Website behaved as expected and showed required Email to be filled in.

- Scenario Five - Incorrect Email format
Steps to test:
    1. Go to Sign up page from home page
    2. Input following data into form:
        - First Name: John
        - Last Name: Smith
        - Email: John_Smithtest.com
    3. Click Sign Up button

Expected:

Form does not submit and shows the email format is incorrect and requires correct format.

Actual:

Website behaved as expected and showed the email format is incorrect and requires correct format.

### Social Media Links

Testing for social media links in the footer area to make sure they open in a new tab.
- These were tested by clicking each one and behaved as expected opening in a new tab.


## Validator Testing

- HTML
    - No errors were found when testing website through W3C HTML Validator

![image of test result for home page through HTML validator](docs/readme_images/htmlvalidation.png)
![image of test result for gallery page through HTML validator](docs/readme_images/gallery_htmlvalidation.png)
![image of test result for sign up page through HTML validator](docs/readme_images/signup_htmlvalidation.png)

- CSS 
    - No errors were found when testing website through W3C CSS Validator

![image of test result for home page through CSS validator](docs/readme_images/cssvalidation.png)
![image of test result for gallery page through CSS validator](docs/readme_images/gallery_cssvalidation.png)
![image of test result for sign up page through HTML validator](docs/readme_images/signup_cssvalidation.png)

## Unfixed Bugs

The website worked on all devices as it should and I found no errors or bugs to fix at this time.

## Deployment

This website was deployed using GitHub pages

- Steps to deploy
    1. In GitHub repository, go to Setting tab
    2. From the Branch drop-down menu section, select main
    3. After saving from step 2, the page will be deployed and a live link will display after a few moments.

A live link can be found here - https://rtguinn.github.io/p1-tgm-basketball-signp/

# Credits

## Content
- This website began following the Love Running project from CodeInstitute as a tutorial until the site came into its own..
- CodeInstitute Project 1 sample project was also used a reference
- Mentor Project 1 Taco-travels from Gareth McGirr was used as a reference
- Icons from Font Awesome were used for media links in footer
- Icon from Favicon Generator were used for tab icon

## Media
- All photos on the home page and gallery were used from my personal collection.
