
# RoadHouse BJJ



## Introduction
This is a project I have created for my first assignment in HTML and CSS. The project is for a Brazilian JiuJitsu club called Roadhhouse BJJ. The website is to allow interested parties, current and potential members to find  relevant information about the gym, where it's located and when the classes are along with more information regarding the gym itself. The webpage is fully responsive for devices from 300px to large monitors 1200px +.

![image](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/8a72ea97-abcf-4c92-95e8-4fb16ae507ca)


## Table of Contents
- [Introduction](#introduction)
- [User Experience](#user-experience)
  - [User Stories](#user-stories)
- [Design](#design)
  - [Colour Scheme](#colour-scheme)
  - [Typography](#typography)
  - [Imagery](#imagery)
  - [Wireframes](#wireframes)
- [Features](#features)
  - [Existing Features](#existing-features)
  - [Features to be Added](#features-to-be-added)
- [Testing](#testing)
  - [Validation of Code](#validation-of-code)
  - [Manual Testing](#manual-testing)
  - [Bug resolutions](#bugs)
- [Technologies Used](#technologies-used)
- [Deployment](#deployment)
- [Credits](#credits)
- [Acknowledgements](#acknowledgements)

## User Experience
### User Stories
- User Goals
The user goals for this website are to be able to navigate clearly and effectively across the site and find the information they require whether it be information about the gym, the class shcedule, the gyms facilities or a page to get in touch and schedule a class.
- Site Owner Goals
As the site owner, the goal is to make the website seamless for the user and include all the important and relevant information available to them, while also ensuring the user can easily find the contact tab so they can reserve a class.

## Design
### Colour Scheme
I used the website color-hex.com to find an appropriate colour scheme and decided on the shade and colour
#BEA477. Along with this I chose a secondary colour #CEBB9A for certain sections, along with inverting the text colour
#252525 for the header and footer.

![Main Shade](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/751729ea-e5a3-4630-911e-6f621be89de2)

![Secondary Shade](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/a8ddb947-5348-464b-b909-71670ed2fa80)

![Header, footer and text shafe](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/969cd577-d72a-4c4a-b088-0aced0692cc4)



### Typography
I chose to stick with a sans-serif font type for the entirety of the webpage as it is very clear and easy to read for all users. Body font was 'Roboto', while headings were 'Bebas Neue' of the sans-serif family.
### Imagery
The entirety of my gallery page was found from pexels.com along with the index hero image and the class photo page.owever many other images were used primarily from websites found on google. The coach images were from sherdog.com, a popular MMA site. The about hero image was from bjjfanactics.com and the gym photo from fittinsider.com.

I understand in a real website I would need to have image rights for images used or use free stock sites like pexels or others to ensure I am not breaking any copyright laws.

### Wireframes
I was unable to install balsamiq wireframing tool due to restrictions on the computer I am using, so I opted for a free tool online wireframe.cc . Although it was more difficult to use and didn't allow me plan as effectively as I would have liked, I made some rough wireframes for each page.
![Wireframe for top of index page](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/6e36fd93-1d8d-4f91-bb4d-2cd83efccd65)
![Wireframe for about page top half](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/58aa844e-4572-459f-84b0-a89559975866)
![Wireframe for contact page](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/42f7bcdf-fd96-4ec3-b14a-5e97987786c1)


## Features

### Responsive Navigation Bar toggle
This code was taken from the LoveRunning course to enable this feature using only CSS and HTML and is visible under the nav bar styles on styles.css page.
![nav bar toggle](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/664ea214-f40d-497b-b52c-46746a7c490c)


### Responseive map for directions
![embedded google maps directions](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/36796eba-2e82-47e4-af90-6c06a1bf7b78)


### Footer with working social mediahyperlinks
This code was also taken from the LoveRunning course for ease of use.
![footer with social media icons](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/7fe9d09a-4135-4e38-a6e2-b59a0c1b259e)


### Heading on index page with hyperlink to contact page
![hyperlink to contact form](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/810e0dc0-a4ad-4111-ab1d-9a494bfca157)


### Working contact form which redirects to a thank you page
Although this page doesn't work correctly using github pages due to server restrictions
![contact form](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/964308fe-efa3-4296-ade3-3f1ae1652b4c)

![Contact form redirect page](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/8d945fff-9d72-4344-bc84-7099542501ff)


### Responsive flex box reviews which hide/appear depending on screen size
![Flex review 1](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/97887eef-6f85-4a25-a498-b228c757b1dd)
![Flex review 1 and 2](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/1d569ac2-9f4b-4265-ae8d-4a4e88bd61f4)
![Flex review 1, 2 and 3](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/c7b19665-fe1b-4240-901a-0da14d5cfde3)



### Youtube video
![screenshot of youtube video](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/70ef4f98-69fb-4edf-91fa-726fcc45dda8)

### Working 404 page.
![404 page](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/f8d663c8-b9be-4d54-8dc3-1db0fa440177)


## Features to be Added
I would like to add a feature that would send out an automatic email once a form has been completed letting the end user know that we have received their form submission and will get in touch with them personally while also including an information pack in the email. This could be done by using an API from a company like Twilio, Bird or Mailersend.

A clickable image thread where users can click on an image to open it as a carousel, and scroll through the gallery images by clicking on a toggle, rather than all images being full size.


## Testing

### Validation of Code
Index w3 validator
![w3 validator pass for HTML](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/89b093d0-c8ea-4bd8-a22c-c8ab36f488dc)
CSS Validator
![CSS validator passs](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/f27fbb73-d918-4c5a-a149-9cbeaddd7189)



### Lighthouse
Lighthouse results, it's worth noting that at time of testing my internet speed was not great, with a download speed of roughly 7mbps. Also the image that has caused a low best practices score was compressed multiple times:
![Lighthouse results for index page](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/3c754a53-79ce-4014-b139-bce648c4627a)


Common issue seems to be with image size and type used for mobile versions of the website. In the future I will procure more modern images suited for web design rather than jpg or png.

### Wave Webaim - accessibility testing
Although there is one error, it is not possible to fix this it is regarding an empty form label that is used for the dropdown nav bar option we were taught in the walkthrough project.
![Accessibility testing review from Wave](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/9d8c8d40-7cb9-490d-8fd4-cc0b4f9b3db4)


### Manual Testing

Here I have tested all the features on each and every page of my website. Please see the results below.

Our goals were met in this testing as all pages are directly accessible and easy to find for the user, with clear descriptions where to find certain information along with an acknowledgement when a contact form is sent.

This was tested using a google pixel 6 pro, iphone 11 and responsive mode on a large PC monitor.

Format of the table below is as follows:

| Feature being tested| Expected Outcome | Testing Performed | Actual Outcome | Result (Pass or fail) |



| Header hyperlink index page| Refreshes current page | manually clicked | page refreshed | Result PASS|

| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |

| Header hyperlink about page | directs to index page | manually clicked| directed to index page | Result PASS |

| Header hyperlink gallery page | Directs to Index page | manually clicked | Directed to index page | Result PASS |

| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |

| Header hyperlink contact page | directs to index page | manually clicked | directed to index page | result PASS |

| Footer hyperlinks on index page| direct to social media sites | manually clicked all | All directed | Result PASS |

| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |

| Footer hyperlinks on about page| direct to social media sites  | manually clicked | All Directed | Results PASS |

| Footer hyperlinks on Gallery page| direct to social media sites | manually clicked| All Directed  | Result PASS |

| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |

| Footer hyperlinks on contact page| direct to social media sites  | manually clicked | All Directed | Reult PASS |

| Dropdown toggle index page| menu drops down  | manually clicked | menu appears | Result PASS |

| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |

| Dropdown toggle about page | menu drops down | manually clicked  | menu appears  | Result PASS |


| Dropdown toggle Gallery page| menu drops down | manually clicked | menu appears  | Result PASS |

| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |

| Dropdown toggle contact page | menu drops down | manually clicked  | menu appears | Result PASS  |

| Youtube video about page| Video plays but not automatically | opened about page and clicked play | video only plays when clicked | Result PASS |

| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |

| contact form submission required fields | Can't submit form unless all requried fields are checked| Tested every combination | Required fields prompted if not submitted correctly | result PASS |

| contact form submission| redirected to thank you page | completed form and submitted | redireted to signedup.html | Result PASS |



## Bug resolutions

When writing the html and CSS code for this website, some bugs were found and rectified along the way.

A major bug was the stretching of the Hero image on the index.html page. Due to the size of the image being used, on large screens this image would become stretched and off centre.

To fix this, I used a larger version of the same image (900x) and updated the CSS in a media query for screens of 900px and more to use this image, and update the positional values of the image. The CSS used to overcome this bug is shown below.
![Media query to fix hero image bug](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/699f79fa-dc4e-4dbe-bd53-dd61315b01e4)

Another bug that was found was on the contact form. The contact form page would submit regardless of whether any class choices or contact information was added or not. This was due to the HTML code for the form not containing a required field. This was amended upon finding the issue when conducting manual testing.


## Technologies Used

This project was done solely using HTML and CSS, along with vs code and gitpod.

## Deployment

You can access the website directly through the following link: [ROADHOUSE BJJ](https://mickjitsu.github.io/roadhouse_BJJ/)

Alternatively, you can follow these steps to deploy the website locally:
1. **Clone the Repository:** : https://github.com/Mickjitsu/roadhouse_BJJ.git

2. **Navigate to the Project Directory:** : cd /roadhouse_BJJ

3. **Open the Website:** : Open the main index.html page and navigate across the site




## Credits

The images of this site came from pexels.com , sherdog.com, bjjfanactics.com and fittinsider.com.

The video came from the grappling academys youtube channel. The schedule was created using Abode.com free schedule maker

## Acknowledgements
I would like to thank my partner for encouraging me to continue on when I was struggling at the start of the course, my family for encouraging me to keep studying despite going through a bereavement, and my mentor Matt for helping me along the way with pre, mid point and final calls!

[Back to top](#introduction)
