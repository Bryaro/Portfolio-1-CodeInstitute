Readme Layout

# Kitten Father
Welcome to [The Kitten Father ](https://bryaro.github.io/Portfolio-1-CodeInstitute/)

![image of site](/assets/documentations/Amirespnsivekittenfather.png) Here is a screenshot taken from AmiResponisve website to have a overview and see the site responsive

## Introduction
Welcome to the Kitten Father aka Abu Hurairah Website! 🌟

This site is to explore the life, teachings, and profound wisdom of Abu Hurairah, a key companion of Prophet Muhammad (PBUH). This website is a curated tribute, offering a glimpse into the rich legacy and contributions of Abu Hurairah to Islamic tradition. Whether you're a scholar seeking in-depth knowledge or a curious learner eager to discover, my platform provides a comprehensive resource on the remarkable journey of Abu Hurairah. Join me on this enlightening exploration!


## Features
The website have 3 pages, Home, Biography and Contact(which will be redirect by get method to another link(which for the moment used hidden page called tahnkyou.html) since I made this project only with HTML5 and CSS3 as shown on the tables below)


- **Navigation Bar:** 
The navigation bar is on all three pages. It has links to the Logo, Home page, Biography, and Contact page. The navigation bar looks the same on every page, making it easy to move around.


- **Home:**
The landing page with image/photgraph and overlay text
- **Biography:**
This page is the biography of the kitten father aka abu hurairah. 
This page will have 2 pictures and a video. The video is set to mute and paused, allowing the user to click play and unmute it for a better experience. This way, the user can read the biography first and then choose to listen and watch the video, reducing unnecessary clicks for the user.
- **Contact:**
This page is centered around a contact form. It requires the user to provide their name, surname, email, and information in a textarea. After completing the form, the user will be directed to a concealed "thank you" page.

- **Thankyou:** [click here to view](https://bryaro.github.io/Portfolio-1-CodeInstitute/thankyou.html)
This approach is due to the usage of only HTML5 and CSS3 without involving other languages like JavaScript to handle request. But if javascript was involved then this would been sendig a request after send message submit clicked by the user.

## Table of Contents

| Pages | Name |
|-----:|-----------  |
|     1| Home        |
|     2| Biography   |
|     3| Contact     |
|     4| thankyou    |

The thankyou.html is only to redirect the user to a get request to later use it using with different language e.g javascript


| Count | Lanuages |
|-----:|-----------  |
|     1| HTML5       |
|     2| CSS3        |
|     3| Markdown(for readme)   |

1. [Introduction](https://bryaro.github.io/Portfolio-1-CodeInstitute/)
   - Welcome
   - About Abu Hurairah
   - Purpose of the Website

2. [Biography](https://bryaro.github.io/Portfolio-1-CodeInstitute/biography)
   - Early Life
   - Embracing Islam
   - Companion of Prophet Muhammad (PBUH)
   - Notable Events

3. [Contact](https://bryaro.github.io/Portfolio-1-CodeInstitute/contact)
   - Get in Touch
   - Social Media

## Technologies Used

### Frontend
- **HTML5:** The structure of the web pages is created using HTML5 for semantic markup.
- **CSS3:** Styling is applied using CSS3 to enhance the visual appeal and responsiveness of the site.

### Frameworks and Libraries
- **Font Awesome:** Icons from Font Awesome are used to enhance the visual elements of the navigation bar and the cat on the home page.
- **css:hover:**  This is used over the navbar menu when hovered over it gives the font-weight: 950 and a text-decoration: underline;

### Version Control
- **Git:** Version control is managed using Git, allowing for collaboration and tracking changes throughout the development process.
- **GitHub Pages:** The website is hosted on GitHub Pages, providing a convenient way to showcase the project.

### Deployment
- **GitHub Actions:** Continuous integration and deployment are set up using GitHub Actions to automate the deployment process when changes are pushed to the main branch.

### Other Techniques
- **Responsive Design:** The website is designed to be responsive, ensuring a seamless experience across various devices and screen sizes.
- **SEO Optimization:** Meta tags and other SEO best practices are implemented to enhance the website's visibility on search engines.
- **Accessibility:** Accessibility features are incorporated to ensure a more inclusive user experience for all visitors. ![lighthouse](/assets/documentations/lighthousekittenfather2.png)

## Getting Started

To view the website, simply click [here](https://bryaro.github.io/Portfolio-1-CodeInstitute/). If you want to run the project locally, follow the steps below:

1. Clone the repository: `git clone https://github.com/bryaro/Portfolio-1-CodeInstitute.git`
2. Open the `index.html` file in your preferred web browser.

Feel free to explore the different sections of the website and check out my projects. If you have any questions or feedback, don't hesitate to [contact me](https://bryaro.github.io/Portfolio-1-CodeInstitute/contact.html).




<!-- mentors -->
## User Experience
### User Stories
- User Goals
- Site Owner Goals

## Design and technologies Used
### Colour Scheme: [Color Picker w3schools](https://www.w3schools.com/colors/colors_picker.asp)
### Imagery: [Canva pro website](https://www.canva.com/)
### Wireframe: [Balsamiq website](https://balsamiq.com/wireframes/)
### Markdown syntax for this readme file: [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/quickstart-for-writing-on-github

## Features

### Feature title - e.g. Navigation
Screenshot of implemented feature
Description of the value this feature has for the users

Repeat for each feature

## Features to be Added
Feedback page, request to database after user submiting contact form. add of authentic hadith: a collection of traditions containing sayings of the prophet Muhammad which, with accounts of his daily practice (the Sunna), constitute the major source of guidance for Muslims apart from the Koran.

## Testing
#### Validator testing for HTML
 - **homepage:** Result was green with **No Errors** Errors but void elements. used [W3C html Validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbryaro.github.io%2FPortfolio-1-CodeInstitute%2F)

#### Validator testing for CSS
- **CSS:**
Result was green with **No Errors** but warning about imported google fonts [W3C css validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbryaro.github.io%2FPortfolio-1-CodeInstitute%2Fassets%2Fcss%2Fstyle.css&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Lighthouse
![](/assets/documentations/lighthousekittenfather.png)
![](/assets/documentations/lighthousekittenfather2.png)
I've concentrated primarily on accessibility while also giving due attention to best practices, SEO, and performance.

### Wave Webaim - accessibility testing
I've used toggle isntead of javascript and it doesnt give error here because I've added aria-label to the input and the label. but it should give two errors if the aria-label removed. this is because I am using only html and css for respoinsive deisgn.
![wave webiam screenshot](/assets/documentations/Screenshot%202023-12-05%20at%2017.13.12.png)

### Manual Testing




| Feature being tested | Expected Outcome | Testing Performed | Actual Outcome | Result (Pass or fail) |
| -------------------- | ---------------- | ----------------- | -------------- | --------------------- |
| HTML5 | No Error| Yes | 3 Errors | No Error |
| CSS | No Error| Yes | No Error | No Error |

Unfortunately, screenshots were not captured for the HTML validator, but there were three identified errors, namely: 
- Footer: n the footer the list < li > had all the following < l > missing the i before ending of the element. 
- Header: had extra ending of an anchor
- incorrect pathway to images since when deployed the pathway is not as on the computer. had to add ../ to images and media in order for the github pages to find the source of assets.


## Codeanywhere and GitPod forking repository

I used Cloud based IDE, codeanywhere half of the project, but it seemed to be very slow and was keep lagging and so did a bit research on google and slack team. Some recomended me to use gitpod. Tried it and it instantly changed the speed of my deplyment process.
Cloning the Repository using cloud based IDE Codeanywehre or Gitpod.

### if using *Codeanywhere* IDE:
Open Codeanywhere:

Log in to your Codeanywhere account.
Create a New Container:

Create a new container and choose a stack or use an existing one.
Open Terminal:

Within your container, open the terminal.
Clone the Repository:

Use the git clone command followed by the repository URL to clone it into your Codeanywhere workspace.

### if using *GitPod* IDE:
Open Gitpod:

If you're using Gitpod, navigate to the Gitpod website.
Prefix Repository URL:

Add the repository URL in the browser's address bar and press Enter. This opens the repository in a Gitpod workspace. actually almost similar to Codeanywehere cloud based IDE

Forking the Repository:
Using Codeanywhere IDE or Gitpod IDE:
Visit GitHub:

Open your web browser and go to the GitHub page of the repository you want to fork.
Click on "Fork":

Click the "Fork" button at the top right of the page. This creates a copy of the repository in your GitHub account.
Running the Site Locally:
Using Codeanywhere IDE or Gitpod IDE:
Navigate to the Cloned Repository:

Use the file explorer to navigate to the cloned repository.
Run the Site Locally:


To be able for viewing it locally on the port view we need to type the following in a new terminal

---
> python3 -m http.server

## Deployment
Deploying the Site:
Using Codeanywhere IDE or Gitpod IDE:
Choose Hosting Platform:

Decide where you want to deploy the site, like GitHub Pages, Netlify, etc.
Follow Platform-Specific Instructions:

For GitHub Pages, configure the branch in repository settings.
Commit and Push Changes:

Ensure your changes are committed and pushed to the repository.
Wait for Deployment:

Depending on the platform, wait for the deployment to finish.
Access Deployed Site:

Once done, your site should be accessible using the provided URL.
For this website: https://bryaro.github.io/Portfolio-1-CodeInstitute/
![github pages for this website](/assets/documentations/Screenshot%202023-12-05%20at%2017.57.21.png)


## Credits

You need to credit where you got anything for your site from.. where are the images from, are they all from the same site? where did you get the content from, if you wrote it yourself, did you fact check anywhere? did you get code from anywhere? if so, it needs to be clearly marked in both the code and the readme.


Click [here](#kitten-father) to return to the top of the readme.

<!-- BRYAR start -->
<!-- video credit to youtuber: https://www.youtube.com/@VeiledFaith -->
<!-- BRYAR ebd -->

