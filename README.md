# **The Monkees - Code Institute Milestone Project 1**

## The Monkees Band Website
This project is a new design concept for the band ‘The Monkees’. It is built for their fans, and showcases some of their greatest hits, information about the band, and the ability to contact the band for private bookings and all other enquiries. The website includes the Band’s tour dates, and allows fans to sign up for a newsletter so they can stay up to date with their favourite band.

### **UX**

This website is built predominantly for the fans of The Monkees, but also for people who are just discovering the band. The website intends to inform the user of future events that the band will play at, provide links to book tickets, showcase their music and provide a medium for users to contact the band for private hire.

- As a fan of The Monkees, I want to:
1. Visit their website to see their upcoming tour dates and find links to book tickets
2. Listen to some of their greatest hits
3. Contact the band to hire them for a private event
4. Sign up to their newsletter for regular band news 

###  **User Story**
- I am long time fan of The Monkees, and I want an easy way to find out when I can see them perform. I am not very good with technology, so need a website which is simply laid out and easy to navigate.
    1. Upon loading the website, I need to see an obvious place to find when the band is performing
    2. I see the heading in the header menu ‘Tour Dates’ and click on it
    3. I am taken to a page that shows the tour dates.
    4. I would like to book tickets.
    5. I see there are buttons to click which say ‘Book Now’. These take me to an external website where I can purchase the tickets.
- I am someone who has just come across the band The Monkees, and I want to find out more about the band and listen to some of their music.
    1. When on the website, I want to see an obvious place to find information
    2. I see there’s a tab called ‘About’
    3. I click on it, and I am taken to a page with information about the band.
    4. Now I want to listen to some music.
    5. I navigate to the tab called ‘Gallery’, which has music to listen to and a music video so I can get a taste of what the band members are (were) like.
---
### **The Monkees Website - UX Brief**
#### **Strategy:**
What are you aiming to achieve?
- I am aiming to produce a slick and informative site for fans of ‘The Monkees’
It will be responsive to all devices and browsers

#### **Scope:**
What features do you want to include?
- It will showcase:
    1. Music videos, audio and images from the band.
    2. A a short biography of the band, and then individual photos of each member.
- Users will be able to:
    1. Find links to book tickets to live concerts
    2. Contact the band, and enquire to book them for private functions
    3. Sign up to a newsletter
    4. Listen to the Band’s music and watch their music videos.
    5. Read information about the band

#### **Structure / Skeleton:**
How is the information structured, and is it logically grouped?
- The website will include 5 pages:
1. Home
    - Showcasing the music video for ‘Daydream Believer’
    - Very simple - not hit with lots of information
2. About
    - Biography of the band
    - Photos of the band members
3. Gallery
    - Pictures of the band
    - Album artworks
    - Audio tracks of some of the Monkees most iconic songs
    - Music video
4. Contact
    - Form for users to get in contact with the band, and also make enquiries about hiring the band for private events
5. Tour Dates
    - A timeline with some of the Monkees tour dates, with functional buttons to book tickets to real Monkees concerts.

***The website will have the same header and footer on every page***

- Header will include:
    - Monkees Logo
    - Menu of every page in the website
    - Social media icons and links for facebook, twitter and youtube (on desktop only, on tablet devices and smaller, these icons will appear in the footer, so the header isn’t too cluttered)
    - An audio track

- Footer will include:
    - Contact us button, that links to the ‘Contact’ page
    - A newsletter sign up box
    - On tablet devices and smaller, the social icons, which on desktop appear in the header will appear here, in the footer.

#### **Surface:**
- Color Scheme
    - The colour scheme will be matched from an old Monkees band logo (#F62F2F (light brilliant red) and #FFFDE8 (creamy white)), which will be alternated for different elements and features. (Cream text on red or vice-versa)
- Font Family
    - 'Monoton’ for a retro look (Google Fonts)
- Images
    - Images will be photos of The Monkees and their album covers.

---

### **Features**

#### **Existing Features**
- The Header - allows the users to navigate the website by having clear links to the other pages within the website. It also includes one audio track, so the user can listen to music as they browse the website. The header also features links to the band’s social media channels, so the users can follow the links to view extra band related content.
- The Footer - allows the users to sign up for the band’s newsletter by filling in their email address. There is also a link to the contact page, and on mobile devices the band’s social links will appear here, so they can access extra band related content.
- The homepage allows users to see a simple menu, to navigate to the relevant page that they were hoping to find, such as ‘About’, ‘Contact’ or ‘Tour Dates’. This page isn’t cluttered with lots of information, so the user isn’t bombarded with text and images. I think this makes it easy to navigate, with clear separation between website sections. There is a music video in the main section of the website, for quick access to the band’s media.
- The Gallery - allows users to listen to the band’s back catalogue, as well as preview some images, and watch a music video.
- The Tour Dates page - allows users to view date and location of the band’s upcoming tour dates, with links to book official tickets.
- The About page allows users to read a short biography of the band.

#### **Features Left to Implement**
1. Ideally, I would make the sound files continue playing while the user is browsing individual pages, rather than stopping and having to restart every time they visit a new page on the website.
2. A shop for users to purchase merchandise would be the next major feature I would include in the website.
3. With more regular information about the band, the homepage has the potential to become a news feed with blog articles to update fans - This would be the same content that fans would receive in the emailed newsletter.
#### **Technologies Used**
1. **HTML5**
- I used HTML5, as it is the base of every website.
2. **CSS**
- I used CSS to style my HTML code, to create a global design scheme, and make the website visually appealing for users.
3. **[Bootstrap](https://getbootstrap.com/)**
- I used Bootstrap’s grid layout to divide my page into sections, which helped keep content in order and evenly spaced around the site. I also made use of some of its predefined styles, mainly for the buttons.
4. **[Hover.css](http://ianlunn.github.io/Hover/)**
- I used this to animate my menu items when they were hovered over to show the website was responding.
5. **[Font Awesome](https://fontawesome.com/icons?d=gallery)**
- I used Font Awesome to source my social media icons.
---
### **Testing**
1. **Tour Dates:**
- I went to ‘Tour Dates’ page
    - Checked all locations and dates of concerts
    - Clicked the button ‘Book Now’ next to corresponding dates, and was successfully taken to a page to book tickets for that particular concert. Links may expire once the events have passed.
2. **Newsletter Sign Up**
 - I went to the newsletter sign up form at the bottom of the homepage.
    - Entered my email correctly, and was taken to a new tab, with a success message (Sometimes this file with the success message loads an error on some servers)
    - I tried entering an invalid email format, and received the error message that I hadn’t entered a valid email.
    - I tried to submit the form without any data entry, and again this showed an error message that I needed to enter a valid email. 
    - I tried this process on every page with the form in the footer, with the same results.
3. **Contact Us Form**
- On the ‘Contact Us’ page, I submitted valid details in all fields, and was taken to a new tab, which confirmed I had submitted valid information successfully. (Sometimes this file with the success message loads an error on some servers)
    - I tried entering invalid data in the fields, and was met with correct error prompts that the data was the wrong format.
    - The same error prompts were shown when no data was entered.
4. **Header Audio**
- I successfully played music from the header audio ‘Our Latest Single’ on every page.
- I was also able to play the sound files on the ‘Gallery’ page and watch the music video.
5. **About Page**
- Testing this page on both desktop and mobile loaded the same content accurately, with the responsive code rendering as it should on the respective screen sizes.

### **Responsiveness**
Using the chrome inspector tool, I tested different screen sizes, to see how the menu would respond. With the button that I added for the tour dates I had to use different paddings and margins than with the list items in the menu, so it took some playing around with at different screen sizes. With trial and error, I found what worked with dev tools, and implemented the changes with media queries. I have put a lot of time into ensuring that the website is just as good for mobile as it is desktop.

- One of the notable absences in this project when on mobile or smaller screens, is a hamburger menu. I put some thought into this, and having imagined that a lot of the fans of The Monkees would be of an older generation, I concluded that having the menu visible from the start was more intuitive. 
- Admittedly, on the very small devices there is a minor overlap on the text for 2 menu items, where they are touching the edge of the screen. It is not too much of an offensive bug, so I have not yet spent the time to correct it.
- There is also extra padding below the footer of the Homepage, however I haven't been able to find what is causing this.

**All tests were done individually on Firefox, Chrome, Safari on Mac and iOS, and returned the same results. I have been unable to test Edge and Internet Explorer, or any browsers on PC.**

---

### **Deployment**
- TBC

---

### **Credits**

**Content**
- The text for the ‘About’ page came from the Monkees Wikipedia page, which can be found here: https://en.wikipedia.org/wiki/The_Monkees
- As noted in my code, inspiration and framework for the design of the timeline element on the ‘Tour Dates’ page came from the User Centric Frontend Development module of the Code Institute course.

**Media**
- The media, including audio, videos and photos came from a downloadable file, provided by Code Institute, for use with this project. I also found a separate logo online, which I got from this link https://4vector.com/free-vector/monkees-33349

**Acknowledgements**
- I received inspiration for the design of this project from previous Monkees artwork, particularly in regards to the colour scheme.
- I also took into consideration the era that the band was originally from, and tried to style it accordingly. An example of this would be the use of the ‘Monoton’ font, which gives the website a retro feel.
