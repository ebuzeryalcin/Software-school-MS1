<p align="center">
  <img src="assets/images/sslogo.PNG" 
alt="Software School logo"/>
</p>

![Image that contains example of responsiveness within several screens](assets/images/responsive.PNG)

# Content 
1. [Introduction](#introduction)
2. [UX](#ux)
3. [Wireframe](#wireframe)
4. [Visual Identity](#visualidentity)    
5. [Site Overview](#siteoverview)
6. [User Stories](#userstories)
7. [Testing](#testing)
8. [Deployment](#deployment)
9. [Code Validation](#codevalidation)
10. [Technologies](#technologies)
11. [Media](#media)
9. [Acknowledgements and thanks](#acknowledgements)


## Introduction <a name="introduction"></a>

Software School is an education and mentoring business that offers courses to study in classrooms and online. And conferences is also offered at, for example, trade fairs and companies for skills development.
It was created by a student who studies at the Code Institute and who has ambitions to become a Software Developer.
The content creator knows how important it is to study in the right way and in a flexible environment when needed.

*This site has been created for a school business project and for the exercise purposes. 
This is my first project for the Code Institute Diploma in Full Stack Development.*

## UX <a name="ux"></a>

My goal was to have an intuitive, professional and stylish website. Since all content is on one page, the main function is to easily
access the sections and navigate to the contact form, to contact the content creator. The navigation bar is looking simple and clean, and takes you to different parts of the page in one click.
The appearance of the page looks the same from top to bottom.


- **Home section:**

The design of the Home section is simple and gives a bright introduction of who the person on the front of this business is. 
The background is clean white which makes the portrait, name and title stand out. 
There is also a "Go to Courses" button, the goal is to showcase the offered courses and to make it easier navigationg to the courses section. 

- **Education section:**

This section is simple and clear. There are two different methods to study. Either you study in a classroom or online. 
In classrooms you study for three months and when studying online there is no time limit. The business also offers conferences, 
for example, speech can be kept for training and general understanding of what programmers do.

- **Courses section:**

In this section, responsive layout is achieved using grids. The first course contains languages for learning Front-End Development. 
The second course contains Python and MySql and the third course is about Django. 
Each course has its own Modal pop-up which opens when you click on the "Description" button. 
The Modal pop-up contains information about how many ects points the course gives and that you get a certificate immediately. Each Modal also contains an introductory clip. 
The clips have been added from Youtube using embed links.There is also information about the tutor, what rating the course has received and special discounts. 

- **Contact section:**

The contact section follows the theme of Bootstrap horizontal grid system, which includes booking forms for contacting the school. 
Contact information includes name, email address and a message input. By filling out the form, and submitting it by clicking send button 
target attribute is received at a blank page with information needed.

- **Footer:**

I divided my footer section into two parts. On one part I wanted to add a small presentation about the mentor / tutor. 
After the short presentation, there is contact information, telephone number and email address for the school. 
Then there are also buttons that take us to social media. The second part is Quick Links, by selecting a button you are 
taken directly to a specific section, which makes the user-friendliness better and the navigation much easier.

The total size of the images was shown to be large, which means that the page loads more slowly. I used [tinypng.com](https://tinypng.com/) to compress the file sizes.
The overall reduction in image file sizes decreased by 41% (70 KB).

![tinypng image size saving results](assets/images/tinypng.PNG)


## Wireframe <a name="wireframe"></a>

My wireframe was designed using [Moqups Online App](https://moqups.com/)
I created one wireframe for the html page, the desktop view. My plan was that the page would look as similar 
as possible in the desktop, tablet and mobile versions. 


* Below is a link to my wireframe:

[Wireframe Software-school-MS1](https://app.moqups.com/9m58TR1mq0/view/page/a9bb1465e)

## Visual Identity <a name="visualidentity"></a>

Visual identity
I wanted to give the page a professional character, and to give that feeling I used a stylish look on the whole page.
On the website itself, I chose colors as support so that it became easier to visually distinguish and separate areas. 
The choice of colors, the appearance of the buttons makes it easier for users to distinguish parts of the page and it is easier 
to figure out what different parts of the page mean, which leads to continuity. For example, the percentage and color choice of 
discounts attracts the eye and is a way to get users interested. Another example, the Description buttons on the courses have the 
same look, the hover behavior is the same and one click takes us to the Modal pop-up. By clicking on one of the description buttons 
and exiting it, the user understands that the other description buttons also contain information. It gives depth to the page and users 
stay longer on the page, which increases the chance that people will go ahead and contact the business.

Another way in which I used color to combine things around the site was the hovering behavior with links. I set all links to change 
to the same light green color when you hover on / click on and also the modal buttons. When it comes to the navigation links, 
in addition to the color, I also set these to briefly switch to italics for extra effect.

The visual identity page is consistent. By using the same design, from blue to white and so on throughout the page, the visuals continue 
from the top of the page all the way down. In the footer section, I chose to use a gray color to distinguish it from previous parts of the page.
There is also a Back To Top button throughout the page to make it easy to navigate to top of the page. 

### Site overview <a name="siteoverview"></a>

Series of images of the site is shown below:


![Navbar](assets/images/navbar.PNG)


![Home Section](assets/images/home.PNG)


![Education Section](assets/images/education.PNG)


![Courses Section](assets/images/courses1.PNG)


![Courses Section Modal pop-up](assets/images/courses2.PNG)


![Contact Section](assets/images/contact.PNG)

![Footer](assets/images/footer.PNG)


## User Stories <a name="userstories"></a>


**Users:**

- As a user, I'd like to find information that online courses is available.
- As a user, I'd like to find information that classroom courses is available.
- As a user, I'd like to know more about courses the content creator offers.
- As a user, I'd like to know that the content creator also gives conferences.
- As a user, I'd like to know that the content creator have an experienced career in programming, so I can trust his tutoring/mentoring. 
- As a user, I'd like to see the location?(classroom, add classroom online in description) 
- As a user, I'd like to call but also contact them by writing a message or mail. 
- As a user, I'd like to easily connect with the content creator. 
- As a user, I'd like to know that the content creator uses social media platforms. 


**Software School content creator:**

- As a content creator, I'd like to attrect people to my website so they can learn programming. 
- As a content creator, I'd like to promote the school with a clean and proffessional page. 
- As a content creator, I'd like to promote different education plans that I offer to people.
- As a content creator, I'd like to promote the courses I offer online and in classrooms. 
- As a content creator, I'd like to gain trust of potential customers by having a noticible and ideal website with straightforward information about what courses I offer.
- As a content creator, I want show that people can trust my services by clearly informing that I am a Senior Full Stack Developer and by having an "About me" part on the Footer section.
- As a content creator, I'd like for potential customers to have a very clear idea of all the services I offer and pricing,
as well as the areas covered. 
- As a content creator, I'd like to show people that I am an active social media user by inserting buttons on the Footer section.
- As a content creator, I add contact information on several parts of the page to show that it is easy to approach me.