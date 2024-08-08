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
![Dream Life Menu](documentation/menu.png)

![Dream Life Burger Menu](documentation/burger-menu.png)

# Testing

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
