
# RoadHouse BJJ



## Introduction
This is a project I have created for my first assignment in HTML and CSS. The project is for a Brazilian JiuJitsu club called Roadhhouse BJJ. The website is to allow interested parties, current and potential members to find  relevant information about the gym, where it's located and when the classes are along with more infortmation regarding the gym itself.

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

![Secondary Shafe](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/a8ddb947-5348-464b-b909-71670ed2fa80)

![Header, footer and text shafe](https://github.com/Mickjitsu/roadhouse_BJJ/assets/81781555/969cd577-d72a-4c4a-b088-0aced0692cc4)



### Typography
I chose to stick with a sans-serif font type for the entirety of the webpage as it is very clear and easy to read for all users. Body font was 'Roboto', while headings were 'Bebas Neue' of the sans-serif family.
### Imagery
The entirety of my gallery page was found from pexels.com, however many other images were used primarily from google images. Although I understand in a real situation I would need to use stock or owned photography, as this was a project and not a public websit, I obtained my hero images and about page images from various sources on google images.
### Wireframes
I was unable to install balsamiq wireframing tool due to restrictions on the computer I am using, so I opted for a free tool online wireframe.cc . Although it was more difficult to use and didn't allow me plan as effectively as I would have liked, I made some rough wireframes for each page.
![Wireframe for index page (top half)](image-4.png)
![wireframe for about page (top half)](image-5.png)
![wireframe for contact page](image-6.png)
### Figma/Full color mockup if produced

## Features

### Responsive Navigation Bar toggle
![Nav bar Large screens](image-7.png)
![Nav bar for small screens](image-8.png)

### Responseive map for directions
![Map on large screens](image-9.png)
![Map on small screens](image-10.png)

### Footer with working social mediahyperlinks
![Footer icons](image-11.png)

### Heading on index page with hyperlink to contact page
![Alt text](image-12.png)

### Working contact form which redirects to a thank you page
![Contact form](image-13.png)
![Thank you page](image-14.png)

### Responsive flex box reviews which hide/appear depending on screen size
![Small screen](image-15.png)
![Medium Screen](image-16.png)
![Large screen](image-17.png)

### Youtube video
![Video on about page](image-18.png)
## Features to be Added
I would like to add a feature that would send out an automatic email once a form has been completed letting the end user know that we have received their form submission and will get in touch with them personally while also including an information pack in the email. This could be done by using an API from a company like Twilio, Bird or Mailersend.

A clickable image thread where users can click on an image to open it and scroll through the gallery images by clicking on a toggle, rather than all images being full size.


## Testing

### Validation of Code
Index w3 validator
![index page](image-19.png)
![about page](image-20.png)
![gallery page](image-21.png)
![contact page](image-22.png)

### Lighthouse
Lighthouse results, it's worth noting that at time of testing my internet speed was not great, with a download speed of roughly 7mbps:
![index desktop](image-23.png)
![index mobile](image-24.png)
![Index mobile diagnostics info](image-25.png)
![About us desktop](image-26.png)
![About us mobile](image-27.png)
![Gallery desktop](image-28.png)
![Gallery Mobile](image-29.png)
![Gallery mobile info](image-30.png)
![Contact desktop](image-31.png)
![Contact mobile](image-32.png)

Common issue seems to be with image size and type used for mobile versions of the website. In the future I will procure more modern images suited for web design rather than jpg or png.

### Wave Webaim - accessibility testing
![Wave evaluation](image-33.png)
Although there is one error, it is not possible to fix this it is regarding an empty form label that is used for the dropdown nav bar option we were taught in the walkthrough project.

### Manual Testing

You need to perform, and document everything you did to manually test your site.
At a minimum - you need to check every link on every page works as intended.
So that is check every link in the nav bar (do this on every single page because its a link in a different file) and any other links that appear on your site.
Test the responsiveness of the site - you can do this in the dev tools in responsive mode.
You should also load the site once deployed on as many devices you have access to. What is different from one device to the next? why is it different?

Test the user stories that you created earlier in the readme - did you satisfy the goal, how?

To write up the tests you can use a table,
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

| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |
| enter details here | enter details here | enter details here | enter details here | enter details here |



You should have tests for every section of every page.. individually.

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

Back to top link to return to the top of the readme.
