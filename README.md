<p align="center">
<img src="documentation/logo.png" border="10"/>
</p>

# Dream Life Fitness 

Dream Life Fitness Club is a website that heavily promotes personal training for a healthy lifestyle routine. DLFC is based on a four-core value system and is proud of its excellent location, workout sessions, a plethora of activities, and physical and mental health improvement. The website invites individuals to obtain a workout membership and hopes to help keep people motivated to meet up with its personal trainer for workout sessions regularly. The website will be targeted towards individuals or groups of people who are looking for a way to improve their well-being and keep themselves fit. Dream Life Fitness Club is useful for individuals of all ages, and allows them to seek information about a healthy lifestyle while encouraging physical exercise. The visitors of the website can contact the personal trainer directly, or enquire about a new membership with activities of their preference. 

The website can be accessed via the following <a href="https://evapalatou.github.io/dream-life-fitness/index.html" target="_blank">link</a>.

![Dream Life Mockup](documentation/mockup.png)

# Introduction
The purpose of this project is to create a user-friendly and effective platform that can manage large amounts of clients who are looking to get informed on personal training sessions and are seeking personalized exercise activities in the fitness club or outdoors. Additionally, the clients are requested to choose whether they wish to include nutrition consultation for the duration of the workout membership.

## User Stories
- As a **first-time visitor**, I would like to easily understand the main purpose of the website, so that I can learn more about the fitness club and the services that are offered. Furthermore, I would like to be able to navigate the website and access the content quickly. Finally, it is important to read any testimonials to see whether the fitness club is reliable and credible. 
- As a **returning visitor**, I would like to meet my personal trainer and be able to see his expertise and his professional experience. I would like to view more information about the workout activities that are taking place inside the fitness club and outdoors, in order to ask questions about availability, equipment, and pricelist. Finally, I want to be able to choose a full-blown personalized package that includes both workout and nutrition consultation. 
- As a **frequent visitor**, I would like to be able to keep in touch with my personal trainer about any changes to the class schedule and the exact location of the activities. Moreover, I would like to have the option to freely communicate with the fitness club about my progress or any new additions made to training packages. Last, but not least, it is important for me to follow any social media pages so that I am informed about any discounts, new activities, and contests that are currently running in the fitness club.  


# Features
### Navbar
- Navigation bar is positioned on the top of the page and contains the logo of the fitness club. 

![Dream Life Menu](documentation/menu.png)

- Burger menu is fully responsive on mobile devices.

![Dream Life Burger Menu](documentation/burger-menu.png)

### Footer
- The footer contains links to social media channels that open in a new window.

![Dream Life Footer](documentation/footer.png)

### Button
- The button acts like quick navigation link for the contact page.

![Dream Life Button](documentation/button.png)

### Flip Cards
- Hoverable flip cards with 3D effect provide contact information about the fitness club such as opening hours, address, phone number, contact e-mail. 

![Dream Life Flip Cards](documentation/flip-cards.png)

### Testimonials
- Flex Boxes testimonials section with reviews from our satisfied clients.

![Dream Life Testimonials](documentation/testimonials.png)

### Google Maps
- iframe google maps component with the exact location of the fitness club.

![Dream Life Google Map](documentation/map.png)

### Contact Form
- Instant message contact form inside the about page in order to contact the trainer in person.

![Dream Life Contact Form](documentation/contact-form.png)

### Image Gallery
- JavaScript gallery that includes images with all available activities. The controls of the gallery are designed for color blindness.

![Dream Life Image Gallery](documentation/gallery.png)

### Featured Products
- Featured products list section that hightlights fitness club's special activities.

![Dream Life Image Gallery](documentation/product-list.png)

### Membership Form
- User signup functionality to create a personalised membership via the website.

![Dream Life Membership Form](documentation/membership-form.png) 

## Technologies
- HTML is used as the main structure of the website
- CSS is used to add the styles and layout of the website
- <a href="https://fontawesome.com/" target="_blank">Font Awesome</a> icons to make HTML code appear more descriptive
- <a href="https://marvelapp.com/" target="_blank">Marvel App</a> is used to make wireframes for the website
- JavaScript is used to develop the slideshow gallery within the website
- <a href="https://color.adobe.com/create/color-wheel" target="_blank">Adobe Color</a> palette generator for the user interface aesthetic feel

## Design
### Wireframes
- The wireframes created in Marvel App depict the final design and structure of the website

![Dream Life Wireframes](documentation/wireframes.png) 

### Color Scheme
- The color palette of the website is based on the generic gradient color scheme. Dark and Lighter blue is used for the main content, whilst bright and soft orange for highlighting purposes (i.e. buttons, links, hover effect) 

![Dream Life Colors](documentation/colors.png) 

### Typography
- The project utilizes the Kanit and Roboto font families for typography, providing a clean and modern aesthetic. The color scheme incorporates shades of white, dark blue, and orange, enhancing readability and visual appeal.

![Dream Life Kanit](documentation/kanit.png) 

![Dream Life Roboto](documentation/roboto.png) 

# Testing
## Browser Compatibility
- The website was tested on the following browsers: Chrome, Firefox, Opera

Chrome
![Dream Life chrome capture](testing/capture-chrome.png) 

Firefox
![Dream Life firefox capture](testing/capture-firefox.png) 

Opera
![Dream Life opera capture](testing/capture-safari.png) 

## Responsiveness
- The website was checked both by devtools implemented in Chrome browser and the Website Responsive Testing Tool (source: http://responsivetesttool.com/)

Chrome devtools
![Dream Life responsive home](testing/responsive-home.jpg) 

Website Responsive Testing Tool
![Dream Life responsive home](testing/responsive-home2.jpg) 

## Code Validation
- No errors or warnings were found when passing through the official W3C validator (HTML and CSS)

Home Page
![Dream Life validation home](testing/validation-home.png)

About Page
![Dream Life validation about](testing/validation-about.png)

Gallery Page
![Dream Life validation gallery](testing/validation-gallery.png)

Order Page
![Dream Life validation order](testing/validation-order.png)

Contact Page
![Dream Life validation contact](testing/validation-contact.png)

CSS jigsaw - one warning
![Dream Life validation css](testing/validation-css.png)
![Dream Life validation warning](testing/validation-warning.png)
## Features Testing

| Feature | Test case | Outcome |
| --- | --- | --- |
| Logo | Click on the logo | User is brought to the Home Page | 
| Navbar Home | Click on the "Home" link | The user is redirected to the main page | 
| Navbar About | Click on the "About" link | The user is redirected to the about page | 
| Navbar Gallery | Click on the "Gallery" link | The user is redirected to the gallery page | 
| Navbar Order | Click on the "Order" link | The user is redirected to the order page | 
| Navbar Contact | Click on the "Contact" link | The user is redirected to the contact page |
| Button Subscribe | Click on the "Subscribe" button | The user is redirected to the contact page | 
| Flip Cards | Hover over the first image | The user obtains class schedule information | 
| Flip Cards | Hover over the second image | The user views the address of the fitness club | 
| Flip Cards | Hover over the third image | The user views contact details |
| Google Maps | Click on Google maps iframe | The user uses scroll to zoom the map |
| Footer Facebook | Click on the Facebook icon | The user is redirected to the Facebook page |
| Footer Instagram | Click on the Instagram icon | The user is redirected to the Instagram page |
| Footer Linkedin | Click on the Linkedin icon | The user is redirected to the Linkedin page |
| Footer YouTube | Click on the YouTube icon | The user is redirected to the YouTube page |
| About form | Submit an empty form | Error signaling required fileds |
| About form | Submit a message form | The user is redirected to the Code Institute's dump form page |
| About form | Click on the Reset button | The user clears any text inputs |
| Gallery page | Click on the right control of the slideshow | The user is able to view more images |
| Order page | Click on the "Contact" button | The user is redirected to the contact page to signup the form | 
| Contact form | Submit an empty form | Error signaling required fileds |
| Contact form | Submit a membership form | The user is redirected to the Code Institute's dump form page |
| Contact form | Click on the Reset button | The user clears any text inputs |

## Lighthouse
- Using lighthouse in devtools, it is confirmed that the website is performing well and it is accessible. However, in most of the pages, the overall performance counts 80% which indicates that further improvements need to be made.

Home Page
![Dream Life lighthouse home](testing/lighthouse-home.png)

About Page
![Dream Life lighthouse about](testing/lighthouse-about.png)

Gallery Page
![Dream Life lighthouse gallery](testing/lighthouse-gallery.png)

Order Page
![Dream Life lighthouse order](testing/lighthouse-order.png)

Contact Page
![Dream Life lighthouse contact](testing/lighthouse-contact.png)

## Accessibility
- Using WAVE tool, it is confirmed that the website has passed the accessibility test, as shown previously as well via the lighthouse reports.

![Dream Life Accessibility](testing/accessibility.png)

## Bugs

1. Add bootstrap code to introductory text at the home page.
- Solution:
2. Resize the images at the flip cards section on the home page.
- Solution:
3. Add hover effect on social media icons at the footer section.
- Solution:
4. Create a thank you page for the message form at about page.
- Solution:
5. Center product cards container at the order page.
- Solution:
6. Remove JavaScript elements from the website, might cause poor overall performance.
- Solution:


# Deployment

# Future Improvements

# Credits

# Acknowledgements


To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py` if your Python file is named `app.py`, of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

By Default, Gitpod gives you superuser security privileges. Therefore, you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you, so do not share it. If you accidentally make it public, you can create a new one with _Regenerate API Key_.

### Connecting your Mongo database

- **Connect to Mongo CLI on a IDE**
- navigate to your MongoDB Clusters Sandbox
- click **"Connect"** button
- select **"Connect with the MongoDB shell"**
- select **"I have the mongo shell installed"**
- choose **mongosh (2.0 or later)** for : **"Select your mongo shell version"**
- choose option: **"Run your connection string in your command line"**
- in the terminal, paste the copied code `mongo "mongodb+srv://<CLUSTER-NAME>.mongodb.net/<DBname>" --apiVersion 1 --username <USERNAME>`
  - replace all `<angle-bracket>` keys with your own data
- enter password _(will not echo **\*\*\*\*** on screen)_

------

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**June 18, 2024,** Add Mongo back into template

**June 14, 2024,** Temporarily remove Mongo until the key issue is resolved

**May 28 2024:** Fix Mongo and Links installs

**April 26 2024:** Update node version to 16

**September 20 2023:** Update Python version to 3.9.17.

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
