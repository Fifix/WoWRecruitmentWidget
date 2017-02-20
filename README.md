# WoWRecruitmentWidget
A barebones & lightweight (~155ko of images, ~5ko of HTML code) World of Warcraft recruitment widget, for any guild website.

This widget only uses HTML and CSS, thus enabling you to add this widget to your website without relying on a particular server configuration or content management system (For the record, I've done it for a GuildLaunch-hosted website)
Caution : There's no administration tool linked to that widget, so configuring it requires basic knowledge of HTML/CSS (since you're going to modify the HTML code by yourself; don't worry, it's easy to do so).

# Installation
- Download this project's contents.
- Upload the contents of the img folder to your website
- Copy-paste the HTML code in your website (or add a custom HTML widget and copy-paste the code there, if you're using a CMS).
- If necessary, change the src of each image in the HTML code.
- ????
- Profit.

# Configuration
The configuration of the widget is done by hand (the people handling guild recruitment will only need to know how to change a CSS class).
- The code has two classes : closed and open
- For each class spec, there's a <td class="open|closed">TheImageOfTheClassSpec</td>
- Put open or closed for the class spec you want to open/close to recruitment. Save your changes. Refresh to ensure that your job is done correctly. Job's done.
