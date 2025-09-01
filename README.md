# worldawaits_blog

## Table of Contents:

- Project Overview
- Purpose
  - Business Goals
  - Target Users
  - User Needs
- User Stories Overview
- Website Structure
  - Menu
  - Wireframes
- Features
- Technologies Used
- Deployment & Local Development
- Testing
- Stretch Goals
- Future Enhancements
- Credits

#### A dynamic travel story blog built with HTML, CSS, JavaScript, Python, and Django, deployed on Heroku. The blog showcases travel stories and experiences, while enabling user interaction.

### Project Overview

The Travel Blog is a content-rich website for sharing and exploring travel stories.  
It allows readers to browse personal travel experiences, while also engaging with the community by liking, commenting, and subscribing.

### Purpose

#### - Business Goals

- Grow an engaged audience via interactive content and social sharing.
- Foster community around authentic travel experiences.

#### - Target Users

- Travel Enthusiasts looking for inspiration and real-world experiences.
- Content Creators who want to contribute stories and reviews and be part of a travel experience community.
- Followers who want to keep up with a favorite blogger’s journey.

#### - User Needs

- Browse travel content by category.
- Interact via likes, comments, and subscriptions.
- Create accounts to save preferences and post content.
- Follow the blog on social media.

### User Stories Overview

See Projects page in the travel-world Github repository for complete user stories (LINK: https://github.com/users/limcaroline/projects/8/views/1)

Home Page
As a travel enthusiastI want to see an attractive and welcoming home page with highlights of travel contentSo that I can quickly get inspired and navigate to the stories that interest me.
Acceptance Criteria:

Display featured travel stories or destinations.
Include quick navigation to About, Travel Stories, and Contact sections.
Mobile and desktop responsive design.
Tasks:

- Add navigation menu with links to key sections.

- Test and apply responsiveness on various screen sizes.

- Optimize images for fast load time.

User Registration & Accounts

As a visitorI want to create a personal accountso that I can like, comment, post, and subscribe to travel content.

Acceptance Criteria:

Sign-up via email/password or social login.
Option to edit profile (photo, bio, preferences).
Tasks:

- Implement registration form and validation.

- Build profile editing page.

- Store and retrieve profile data from database.

User Login/Logout

As a registered userI want to log in and log out securelyso that my account and data remain private.

Acceptance Criteria:

Enable login
Confirmation of logout.
Tasks:

- Build login form with authentication.

- Add logout confirmation prompt.

Post Travel Stories (for owner)

As a content creator I want to post new travel stories with text, images, and videosso that I can share my travel experiences with the community.

Acceptance Criteria:
Enable posting and adding media
Option to save as draft or publish immediately.

Tasks:
Implement draft and publish status.
Add metadata input fields.

Social Media Links in Footer

As a userI want to access the blog’s social media pages from the footerso that I can connect with the blogger on other platforms.

Acceptance Criteria:
Icons for Instagram, YouTube, Facebook.
Opens links in a new tab.
Consistent placement across pages.

Tasks:
Design and add social media icon set.
Link each icon to the correct site.
Add footer to all templates.

As a logged-in userI want to view and write comments on storiesso that I can share my thoughts and interact with the blogger or community.

Acceptance Criteria:

Text input field under each story.
Ability to reply to other comments.
Tasks:

Build comment form and submit handler.
Store and retrieve comments from database.
Style comments section for readability.
Add moderation tools for admin.

Like Content

As a logged-in userI want to like travel stories, itineraries, reviews, and experiencesso that I can show appreciation and help others see popular posts.

Acceptance Criteria:

Heart or thumbs-up icon toggle.
Instant feedback after liking/unliking.
Likes are visible to all users.
Tasks:

Add like button to story templates.
Store likes in database.
Display like counts.

- Good-to-have (future): Labelled as good-to-have in the Projects' user stories board (LINK: https://github.com/users/limcaroline/projects/8/views/1)

### Website Structure

#### - Menu

- Home
- Posts
- Login/Logout

#### - Wireframes
![Wireframe 1 - large screens](static/images/wireframe-1-large-screens.webp)
![Wireframe 2 - large screens](static/images/wireframe-2-large-screens.webp)
![Wireframe 1 - small screens](static/images/wireframe-1-small-screens.webp)
![Wireframe 2 - small screens](static/images/wireframe-2-small-screens.webp)



### Features

- Responsive layout using CSS/Bootstrap - small and large screens
- Summarized snippets of travel stories for viewer selection
- Travel story posts
- Commenting feature

### Technologies Used

#### Languages Used
- Python
- HTML
- CSS
- JavaScript

#### Frameworks, Libraries & Programs Used

- VS Code for local development https://code.visualstudio.com/
- Github for saving and storing files, and version control https://github.com/
- Canva for images and wireframes https://www.canva.com/
- Preview Editor app in MacBook for editing photos https://preview.app/login
- IMAGECOLORPICKER.com to choose color palette https://imagecolorpicker.com/
- Squoosh for converting image file types from png/jpg to. webp https://squoosh.app/
- Google Fonts for typography https://fonts.google.com/
- Font Awesome for icons https://fontawesome.com/
- Favicon.io for generation of favicons https://favicon.io/
- Bootstap Version 5.3 for styling/layout https://getbootstrap.com/
- Autoprefixer for CSS versatility https://autoprefixer.github.io/
- The W3C CSS Validation Service to review codes https://www.w3.org/
- Nu Html Checker to review codes https://validator.nu/
- WebAIM: Contrast Checker to verify contrast for color palette https://webaim.org/resources/contrastchecker/
- Heroku website host https://www.heroku.com/
- Chrome Dev tools for debugging
- Lighthouse for performance testing
- CI/Heroku Pythong Linter https://pep8ci.herokuapp.com/#

### Deployment & Local Development

Github Repo:
Deployment to Heroku: https://theworldawaits-blog-b400a0e5b3e5.herokuapp.com/

#### How to create repo in Github for deployments

I first followed these steps from Code Institute module to create a repo in github:

1. Log into www.github.com. Click the plus icon and select New repository.
2. Name the repository accordingly - Note: I used travel-world.
3. Select Create repository.
4. Copy the commands from … or create a new repository on the command line.
5. In VS Code, use "Open folder" from the file menu to open your vscode-projects folder and create a new project directory.
6. Open a new terminal, and paste in the commands copied from GitHub.
7. You should now see the README.md file appear in the Explorer.

#### How to Deploy

These are the steps to deploy in github that I followed, also referenced from Code Institute's module:

From VSCode, commit and push all your changes to Github.
Go to GitHub repo https://github.com/limcaroline/worldawaits_blog, select Settings, then Pages.
Select the main branch and then Save.
In the Code tab, select Deployments.
On the Deployments page, refresh until the link is provided.
Click the link to check that it is working

#### How to Fork

In Github, go to this Repository: https://github.com/limcaroline/worldawaits_blog
Click the Fork button at the top right of this page to create your own copy of the repo.

#### How to Clone

In Github, go to this Repository: https://github.com/limcaroline/worldawaits_blog
Click the green Code button.
Copy the URL under "HTTPS".
Open your terminal.
Run this command: git clone https://github.com/limcaroline/worldawaits_blog

### Testing

Manual testing
Manually tested the pages for responsiveness, functionality and user experience, including writing posts and comments.

Automated testing
![Python linter](static/images/worldawaits_beach.webp) https://pep8ci.herokuapp.com/#
![Lighthouse testing](static/images/Lighthouse_testing.webp)

### Future Enhancements

- Sharing itineraries and interactive maps - see user stories (good-to-have)

### Credits

Content

- I wrote the content with support from chatGPT and information from TripAdvisor - see 'Acknowledgments' below.

Media
- See also Frameworks, Libraries & Programs Used for more references
- Canva for images
- Bootstap Version 5.3 for styling/layout
- Google Fonts for typography
- Font Awesome for icons

Code

- Bootstrap for cards and similar, also see comments in VSCode https://getbootstrap.com/
- Code Institute's modules and references, including I Think Therefore I Blog, BoardWalk Games and Love Running https://learn.codeinstitute.net/dashboard
- Discord for references and examples
- ChatGPT for helping with ideas, debugging, and structuring https://chatgpt.com/
- Autoprefixer for code prefix on transition
- Django documentation https://docs.djangoproject.com/en/5.2/
- w3schools for python tutorials and materials https://www.w3schools.com/
- learnpython.org for python tutorials and materials https://www.learnpython.org/

Acknowledgments

- Big thanks to Code Institute’s team as well as materials and Level 5 Diploma in Web Application Development modules and walkthrough projects, which I have used as references!
- Special thanks to ChatGPT by OpenAI for assistance in troubleshooting and debugging, as well as support in ideas and structure.
- Thank you to all the mentioned in this readme and in VScode that was helpful in making this project!
