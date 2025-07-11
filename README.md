# Milestone Project One

## A Tail of Two Hearts Dog Shelter Website

This project is based on a fictional dog adoption shelter called A Tail Of Two Hearts. The website's goal is to give the user information about the shelter, its mission and the adoption process while capturing basic information from users. It is aimed to continue to develope to include volunteering opportunities, community events, and information on what donations recieved go towards.

<br>
<br>

## Contents
- [UX](#ux-planning)
  - [Strategy](#strategy)
    - [Business Goals](#business-goals)
    - [Website Goals](#website-goals)
    - [User Personas](#user-personas)
  - [Scope](#scope)
    - [User Stories](#user-stories)
  - [Structure](#structure)
    - [Features we want to include](#features-we-want-to-include)
  - [Skeleton](#skeleton)
    - [Wireframes](#wireframes)
  - [Surface](#surface)
    - [Images](#images)
    - [Colour](#colour)
    - [Fonts](#fonts)
- [Features Included](#features-included)
- [Future Features](#future-features)
- [technology Used](#technology-used)
  - [Languages](#languages)
  - [Libraries And Frameworks](#library-and-framework)
  - [Tools](#tools)
- [Testing](#testing)
  - [Gneral Bugs](#general-bugs)
  - [Responsiveness](#responsiveness)
  - [Code Validation](#code-validation)
  - [Lighthouse Testing](#lighthouse-testing)
- [Credits](#credits)

<br>
<br>

## UX Planning

<br>
<br>

### <u>Strategy</u>

#### **Business goals:**

Primary Goal: Increase dog adoptions.

Secondary Goals: Increase awareness about dog adoption, attract volunteers, raise donations.

<br>

#### **Website Goals:**

From the User's Perspective:

- Discover dogs available for adoption easily.
- Learn about the adoption process.
- Contact the shelter for inquiries or appointments.
- Trust the shelter.
- Navigate easily on desktop and mobile.
- Feel emotionally connected through dog profiles, images, and stories.

From the site owner's perspective:

- Promote adoptable dogs and increase adoption rates.
- Provide important info about the shelter and its mission.
- Collect inquiries or applications via a contact form or call-to-action.
- Build credibility through success stories, testimonials, and partnerships.
- Showcase events (like adoption drives or fundraisers).
- Encourage donations or volunteers.

<br>

#### **User Personas:**

Potential first time dog adopter:
Wants a smaller, calm dog for urban lifestyle and inexperience in adopting. Wants transparency about fees and the process involved.

Donors/Supporters:
Wants to support the shelter through small donations. They want to see the dogs and where their money goes. They need a simple navigation layout.

Animal Lover:
Wants to adopt an older or more high dependency animal. They want more detailed information about the dogs. They want to be able to talk to the shelter both on the phone and in person.

Volunteer:
Wants to support the dog shelter through volunteering. They want information about the roles and the benefit of volunteering with the dog shelter. They want a way to contact the dog shelter regarding volunteering.

Casual Browser:
Browses out of curiosity or general love for animals. They would like more information and some dog pictures to help them decide if they want to engage with the shelter in some way.

<br>
<br>

### <u>Scope</u>

<br>

#### **User Stories**

<u>User Story 1:</u> <br>
As a potential first-time dog adopter, I want to view a list of available dogs with photos and short descriptions, so that I can easily find one that suits my lifestyle.

Acceptance Criteria:

- Dog listings are displayed on a dedicated page or section.
- Each dog has a card or container showing at least: A Photo, name, age, breed, short description
- Cards are styled consistently and clearly
- There is a visual grouping or basic categorization, if possible
- Call to Action

Tasks:

- Create a new HTML page or section for dogs
- Add a Bootstrap-based grid layout to display dog cards responsively
- Use Bootstrap's card component for individual dog profiles
- Ensure each card includes: dog image, dog name, age, breed and short bio
- Adopt me button

<br>

<u>User Story 2:</u> <br>
As a potential first-time dog adopter, I want to understand the step-by-step adoption process, so that I know what to expect before contacting the shelter.

Acceptance Criteria:

- A clear, dedicated section or page explains the adoption process.
- Steps are presented in a simple, logical order with visual cues used for readability (e.g., inquire → meet the dog → home check → adoption)
- Includes information on requirements, fees, and typical timelines

Tasks:

- Create a new section/page titled "How to Adopt"
- Add numbered steps using Bootstrap layout or components
- Include brief explanations of each step.
- Link to the Contact or Dog Listing page from the final step

<br>

<u>User Story 3:</u> <br>
As someone interested in adopting, I want to easily find contact details or a contact form, so that I can quickly reach out to the shelter with questions.

Acceptance Criteria:

- Contact section includes shelter’s phone number, email, and physical address
- A simple contact form
- The section includes shelter hours or response times
- Embedded map image or directions
- Clear heading like “Contact Us” or “Get in Touch”

Tasks:

- Create a “Contact Us” footer section
- Add Bootstrap contact form
- Include static contact details (phone, email, location)

<br>

<u>User Story 4:</u> <br>
As a donor, I want to see a clear option to donate or support the shelter, so that I can contribute financially to help the dogs

Acceptance Criteria:

- A “Donate” button or link is visible in the navigation or hero section
- A donations page explains how funds are used and how to donate
- Includes payment options (even if just informational or external)

Tasks:

- Add a “Donate” link to the navigation bar
- Create a simple donation info section or page
- Explain donation impact (food, vet care, shelter upkeep)
- Include external donation link, if possible
- Donation calls-to-action are present in key places

<br>

<u>User Story 5:</u> <br>
As someone looking to volunteer, I want to find information on how to help or sign up, so that I can get involved with the shelter’s activities.

Acceptance Criteria:

- A volunteer section explains how to get involved (roles, requirements)
- Clear contact or sign-up link is included
- Volunteer benefits or impact are described
- Easily accessible from the navigation or homepage

Tasks:

- Add a “Volunteer” section or as a stand alone page
- Describe different roles (e.g., walking, events, admin help)
- Include volunteer form (doubles as donation form)
- Add images of volunteers

<br>

<u>User Story 6:</u> <br>
As a general visitor, I want to read about the shelter’s mission and see success stories, so that I feel confident in their work and consider adopting or donating.

Acceptance Criteria:

- "About Us" section clearly describes the shelter’s mission and values
- Includes 2–3 real or placeholder success stories/testimonials
- Testimonials include photos, names, or brief stories
- The layout is inviting and emotionally engaging
- The section is accessible from the main menu

Tasks:

- Create an “About Us” page or section
- Add a mission statement and brief shelter history
- Add a “Success Stories” section ( Cards or carousel)
- Use consistent formatting for stories (e.g., name, quote, image)
- Link from homepage to “About” / “success stories”

<br>

<u>User Story 7:</u> <br>
As a first-time visitor, I want to see the shelter’s physical location and opening hours, so that I can plan my visit without needing to call.

Acceptance Criteria:

- Shelter address is clearly listed on the contact page
- Opening hours are listed alongside contact details
- A static map image or embedded map link is available
- The information is mobile-friendly and easy to read

Tasks:

- Add a “Visit Us” or “Location” section to Contact page
- Include address, Google Maps screenshot or link, and opening hours
- Add iconography (location pin, clock) for visual clarity

<br>

<u>User Story 8:</u> <br>
As an animal lover, I want to read full profiles of each dog, including temperament, medical history, and background, so that I can make an informed decision about adoption. (Longer description section for harder to adopt dogs)

Acceptance Criteria:

- Each dog profile includes extended info (temperament, health, history)
- Profiles are consistent in layout and length
- Photos are high-quality and appropriate
- Profiles can be easily found through navigation
- Each profile includes an adopt or contact shelter button

Tasks:

- Create a detailed profile template using a Bootstrap card or section layout
- For each dog, include: Name, breed, age personality/temperament, medical need/history
- Including heart wrenching background story

<br>
<br>

### <u>Structure</u>

<br>

#### **Features we want to include**

Using the user stories, the features I want to use in my project are:

- Collapsable Navbar
- Header with Hero Image and Strapline to use on all pages
- Dog of the Week
- Volunteer Section with Form
- Donation Section with Form
- About section
- Success Stories (carousel)
- Dog Profiles (Modified Bootstrap Cards)
- Adoption Form (Modified Bootstrap Form)
- Advert Sections with links/Call to Actions on homepage for Adopt, Volunteer and Donate Sections.
- Footer
  - Google Maps
  - Contact Info
  - Social Media Links

<br>
<br>

### <u>skeleton</u>

<br>

Combining these features to meet the needs of the Business and the Website's Users I have created these WireFrame Models.

#### Wireframes

- [Mobile Wireframe](docs/wireframe-mobile-ottol.png)

- [Tablet Wireframe](docs/wireframe-tablet-ottol.png)

- [Desktop Wireframe](docs/wireframe-desktop-ottol.png)

<br>

During the process of developement, with feedback from my mentor, I changed to a 'one page' design. This lead to an amalgamation of these Wireframe designs into one design.

<br>
<br>

### <u>Surface</u> 

### Images

I have sourced the Images on pixaybay(CREDIT) and then changed their format to .WEBP for smaller file size resulting in faster load times.

[Pixabay Images](https://pixabay.com/)

<br>

### Colour

The colour scheme inspired by the hero image is:

![Colour palette for Milestone Project One](docs/Dog%20Shelter%20Palette.webp)

<br>

| HEX     | CSS Variable Name       | Actual Colour  | Purpose                                                                                                                                                                                  |   |
|---------|-------------------------|----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---|
| #34646C | --primary-color         | Dark Teal      | This is the brand colour and appears consistently throughout the web-site. It was captured from the hero image and altered for accessibility.                                             |   |
| #925e2a | --secondary-color       | Dark Terracota | This colour is used for emphasis. It was captured from the hero image and altered for accesibility.                                                                                      |   |
| #f0eee8 | --highlight-color-light | Beige          | This colour is is used for making the cards feel like they stand out more by differentiating them from the background. It was captured from the hero image and altered for accesibility. |   |
| #82ddf2 | --highlight-color       | light Teal     | This colour is used to provide a high contrast for hovering over buttons.                                                                                                                |   |
| #ffffff | --font-color            | White          | This colour is used for text where it's background requires a colour other than black for high contrast accessibility and readability.                                                   |   |
| #000000 | --quote-color           | Black          | This colour is used for increasing contrast in text for better accesibility and readability.    

<br>


 I have used a contrast checker to ensure that there is enough contrast for better accessibility and readability, leading to a good user experince.
 
 <br>

 ![Contrast grid for milestone project one](docs/contrast-grid-Milestone-one.webp)

<br>

### Fonts

I have selected a serif font, 'Kranky' for the headings and titles to draw attention, it has a softer feel to it to foster safety and trust. I have selected a sans-serif font, 'Figtree' because of its simplicity and clarity of communication for the text sections.

[Kranky - Google Fonts](https://fonts.google.com/specimen/Kranky)

[Figtree - Google fonts](https://fonts.google.com/specimen/Figtree)

<br>
<br>

## Features Included

<br>

### Navbar

This keeps helps the user navigate easily to different partrs of the page. It remains fixed at the top to reinforce the brand and for ease of access to the nav links.

![Navbar Screenshot](docs/navbar.webp)

### Hero Image

This image is supposed to make an emotional conneciton and inspire people to continue browsing.

![hero image](docs/hero-image.webp)

### About us 

This is section is to build trust with the user and establish credibility. It is supposed to create an emotional connect and invite the user to engage with the rest of the content.

![About Us Screenshot](docs/hero-about-us.webp)

### A Selection of Dogs Available for Adoption

This section is supposed to create an emotional connection and ispire the user into using the call to action on the cards.

![Dog Selection Screenshot](docs/dog-selection.webp)

### Sucess Stories

This section is to build trust through stories from other users and establish credibility.

![Succress Story Carousel Screenshot](docs/success-stories.webp)

### Adoption Information and Form

This section is to invite user to engage with our call to action, our adoption form, and start an interaction with the shelter.

![Adoption Information and Form Screenshot](docs/adoption-information.webp)

### Contact Us / Footer

This section is to provide contact information so that users can see the location and contact details of the shelter. This helps to build trust and transparency.

![Contact Us Footer](docs/contact-footer.webp)

<br>

## Future Features

In the future, if the business wanted to develope the website further then these would be excellent features to add value to the website.

### Volunteering Information

To inspire people to take part in volunteering opportunities at the shelter.

### Donation Section

To inspire people to donate and feel good about doing so.

### Events Section

To increase attendance and participation at events.

<br>
<br>

## Responsiveness

I have used the breakpoints set by Bootstrap for my responsive layouts they are as follows:

![Bootstrap Breakpoints](docs/bootstrap-breakpoints.webp)

## Early Deployment:

I decided to deploy after adding the start of the fist couple of features for testing across multiple devices. This allows for a more agile approach to developement incase things don't work or require changes. This was done through GitHub's deployment feature Located in the pages section of settings. I chose 'Main' rather than 'none' and saved this change. After this I got a link to follow to the deployed version of the site.

[gitHub](https://github.com/)

[Deployed Site](https://gruheem.github.io/milestone-project-one/)

## Technology Used

### Languages
- [HTML](https://www.w3schools.com/html/)
- [CSS](https://www.w3schools.com/css/)

### Libraries
- [Google Fonts](https://fonts.google.com/)
- [Favicon](https://favicon.io/)
- [Font Awsome](https://fontawesome.com/)

### Tools
- [Github](https://github.com/)
- [Balsamig](https://balsamiq.cloud/s9tbtw3/pr7qq27/r2000)
- [Image File Type Converter](https://cloudconvert.com/webp-converter)
- [HTML Validator](https://validator.w3.org/)
- [CSS Validator](https://jigsaw.w3.org/css-validator/)
- [Autoprefixer](https://autoprefixer.github.io/)
- [Am I Responsive](https://ui.dev/amiresponsive)
- [Responsiveness Checker](https://responsivedesignchecker.com/)
- [ChatGPT](https://openai.com/index/chatgpt/)

<br>

## Testing

This website has been tested extensively from its earliest stages of deployment. I have used various tools to check and test the code these are my findings.

<br>

### General Bugs

| Bug                            | Status     | Description                                                                                                               | Resolution                                                                                                |
|--------------------------------|------------|---------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| Carousel stopped working       | Fixed      | The Carousel stopped scrolling and it's buttons stopped working                                                           | Changed the 'data-bs-target' property value to match the 'id' of the carousel                   |
| Button change on hover         | Fixed      | The 'Adopt Now!' button on the navbar chnages shape and position slightly when hovered over                               | Found and changed a typo which occured when swapping the units form px to rem                        |
| Social links responsiveness    | Fixed      | This broke at some point and is no longer appropriate                                                                     | Got rid of the x-axis margin while keeping the y-axis margin for readability                |
| Nav Burger Movement            | Fixed      | The Nav bar spreads over two lines when onvery small screens                                                              | Added media query to shrink h1 slightly on screen size reduciton                  |
| Trailing Slash                 | Unresolved | My Code Formatter put trailing slashes on self closing elements which the code validator does not like                    | I have not figured out how to configure the Formatter to not do this.                      |
| Scroll Padding Stopped Working | Fixed      | The code given by the code institute to collapse the nav dropdown burger after clicking it over rid the scroll padding css| I had chat gpt rewrite this code to fix this one bug as I was not being marked on the borrowed code anyway|
| Burger Menu drops Line         | Fixed      | The burger menu kept being p ushed down a line in certain very small resolution ranges                                    | I added media queries for the font-size of the h1 element so it would all stay on one line                |

### Responsiveness 

I started with the 'mobile first' approach to develpoping this websiote and working on the in increasing screen sizes. Resposnsiveness was tested using Google Chrome Dev Tools, Am I Responsive and Responsiveness Checker. I have tested on a number of simulated and real world devices.

| Size   | Device                   | Screen Size | Navigation | Element Aligment | Content Placement |
|--------|--------------------------|-------------|------------|------------------|-------------------|
| Small  | iPhone 3/4/4s            | 320x480     | Pass       | Pass             | Pass              |
| Small  | Samsung Galaxay s5/s6/s7 | 380x640     | Pass       | Pass             | Pass              |
| Small  | Google Pixel             | 411x731     | Pass       | Pass             | Pass              |
| Medium | iPad Mini                | 768x1024    | Pass       | Pass             | Pass              |
| Medium | iPad Pro                 | 1366x1024   | Pass       | Pass             | Pass              |
| Medium | Nexus 9                  | 1024,768    | Pass       | Pass             | Pass              |
| Large  | Monitor                  | 1600x900    | Pass       | Pass             | Pass              |
| Large  | Monitor                  | 1920x1080   | Pass       | Pass             | Pass              |
| Large  | Monitor                  | 2560x1440   | Pass       | Pass             | Pass              |

Note: The External Links would not work in responsiveness checker so they were tested on chrome dev tools and physical deviced this seems to be a bug with resposiveness checker not my website.

<br>

### Code Validation

#### HTML
One issue found that my iframe had two properties that shoudl have been in my CSS I have moved these across and it is now error free. Formatter introduces a trailing slash error which I have filtered out and logged into my Genral Bugs seciton

![HTML Validation](docs/HTML%20Validation.webp)

#### CSS
There were no errors found in my CSS

<p>
    <a href="https://jigsaw.w3.org/css-validator/check/referer">
        <img style="border:0;width:88px;height:31px"
            src="https://jigsaw.w3.org/css-validator/images/vcss"
            alt="Valid CSS!" />
    </a>
</p>

### Lighthouse Testing

#### <ins>Initial Test:</ins>
This test was performed after adding the 'must-have' features into the project.

![Initial Test](docs/first-lighthouse-score-new.webp)

#### Performance
I used the Lighthouse feature to text my website to see what improverment could be made. It highlighted I was using very large images and could save 25MB on the images across my website. 

#### Accessibility
It highlight some accessibility features I could add like a form label property and an image alt I had missed.

#### Best Practises
Lighthouse did not like how many cookies were used in the google maps iframe I currently do not know how to change this currently. It also highlighted that two images are not always the correct aspect ratio.  It raised the issue that the site.webmanifest link in the head did not have the correct file path.

#### <ins>Intermediate Test:</ins>
After improvements made to my code I was able to achieve a higher score. There are things I would continue to do in order to increase my score further.

![Intermidiate Lighthouse Test](docs/current-lighthouse-scan.webp)

#### Performance
I redownloaded smaller versions and reconverted them to webp files and this made a big improvement to my score and the web page load time. The performance realted improvements were to keep resizing the images more but for only minimal gains and other things which were part code I have used for the website but have not weritten like the Java links.

#### Accessibility 
Accessibility scored 100 which I am happy with. If I wanted to try and make improvements I could look at making the alt descriptions more concise.

#### Best Practises
I added some CSS targeted at the img elements to center and crop the images. I have corrected this site.webmanifest filepath. I am still recieving warning about third party cookies stemming from my iframe. I do not have control over the third party cookies used by google maps.

### <ins>Current State</ins>
After making these improvements I was able to achieve a green score in all three categories.

![Final Lighthouse Test](docs/final-lighthouse.webp)

#### Performance
The performance realted improvements were to further resize the image file, enable text compression, eliminate render-blocking resources and to page prevent back/forward cache restoration. With more time i would look into these and find out what they mean and how to enact them.

![Final Lighthouse Test Performance](docs/final-lighthouse-performance.webp)

#### Accessibility
I am very happy with this score. I believe a properly accessible website is essential with more services moving online everyday. If I was going to try and improve further I could make the image descriptions more concise and interesting. 

![Final Lighthouse Test Accessibility](docs/final-lighthouse-accessibility.webp)

#### Best Practices
I am unsure why Lighthouse is no longer concerned with third party cookies. This is something I would investigate in the future with more time. It's only highlighted incident comes form a screen dimmer I am using which I understand is safe to ignore.

<br> 

## User Story Testing
I was able to complete the essential user stories. Next I would start working on the should have features of the page and finally add the could have features.

| User Story                                                                                                                                                                     | Action                                                                                        | To Do/In progress/completed |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------|-----------------------------|
| As a potential first-time dog adopter, I want to view a list of available dogs with photos and short descriptions, so that I can easily find one that suits my lifestyle.      | Create a selection of dogs to the page with short descriptions of them.                       | Completed                   |
| As a potential first-time dog adopter, I want to understand the step-by-step adoption process, so that I know what to expect before contacting the shelter.                    | Create intruction cards along with what people can expect once they have filled out the form. | Completed                   |
| As someone interested in adopting, I want to easily find contact details or a contact form, so that I can quickly reach out to the shelter with questions.                     | Create a form added with anchor links consistently put throughout the page.                   | Completed                   |
| As a donor, I want to see a clear option to donate or support the shelter, so that I can contribute financially to help the dogs                                               | Create a section with information about how to donate and where the money goes.               | To do                       |
| As someone looking to volunteer, I want to find information on how to help or sign up, so that I can get involved with the shelter’s activities.                               | Create a section where events are listed and contact information for signing up to events.    | To do                       |
| As a general visitor, I want to read about the shelter’s mission and see success stories, so that I feel confident in their work and consider adopting or donating.            | Create a section which contains information about the shelter nad its mission.                | Completed                   |
| As a first-time visitor, I want to see the shelter’s physical location and opening hours, so that I can plan my visit without needing to call.                                 | Create a seciton with contact and address detials with opening times.                         | Completed                   |
| As an animal lover, I want to read full profiles of each dog, including temperament, medical history, and background, so that I can make an informed decision about adoption.  | Create section for harder to adopt dogs with additional information about care needs.         | To do                       |

<br>

After testing our the user stories we can see that we have achieved our MVP, ready to meet our primary goal and one of our secondary goals. We have planned out eveyrthing and have everything in place to continue developement to achieve all secondary goals.

## The future 
Now that we have our MVP website live, the next step would be to fork the project and continue development in a separate branch. This allows us to safely add features, make improvements, and test thoroughly, all the while the original, fully tested version of our site remains deployed and stable for users to interact with.

<br>

## Credits

Thank you to Simen Daehlin, my Mentor,  for his feedback and support.

Thank you to Code Institute Learning Materials for Code tutorials and a snippet of JavaScript used to make the burger dropdown options dispear once you have clicked on it (later modified by Chat GPT).

Thank you to all the websites listed in Technology.

Thank you to Manuel Perez Romero, my Assessor, for taking the time to read this.


