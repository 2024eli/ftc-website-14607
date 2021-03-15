# FTC Robot Uprising

[![Generic badge](https://img.shields.io/badge/Made%20With-Hugo-red?style=for-the-badge&logo=hugo)](https://shields.io/)

[![Generic badge](https://img.shields.io/badge/Hosted%20With-AWS-orange?style=for-the-badge&logo=AWS)](https://shields.io/)


## BIG BOLD NOTICE TO TEAM MEMBERS BEFORE YOU COMMIT - THE SITE REBUILDS AND REDEPLOYS ON EVERY COMMIT YOU MAKE! EVERY REDEPLOY CYCLE TAKES ABOUT 2 MINTUES AND 65 MS. DON'T BE THAT PERSON WHO COMMITS 16 TIMES TO EDIT ONE FILE. PLEASE!

Don't Break Anything  - Dev
Ok keep reading :)

This is the GitHub Repository for the FTC 14607 Team Website. A few guidelines you should read before you fork or contribute (contributing is for team members only):
  - DO NOT Edit the HTML file unless you want to make major changes to the theme (remove navigation menus, etc.)
  - 99% of the time, you only need to update the .md files, which can be found under the "content" subdir
  - DO NOT Edit the Javascript or CSS files unless you know what you are doing

### Why can't I edit files besides the .md files?


Allow me to explain. The site is built with [Hugo](https://gohugo.io/). Hugo is a static site generator. 
##### What is a static site generator?

"Static sites are ones where there is no server side required to render pages, they are just static html, css and javascript served by any flat file web server.
Static site generators create these sites based on some form of input - typically markdown files and page layouts. But these can also be coupled with headless CMSs (aka api driven CMS or flat file CMS) to generate the static pages. The difference between a static site using a headless CMS and a typical CMS is that the site is rendered once when the content changes rather than on each request. For most sites, this is more than adequate and makes them cheaper to run (no server-side load to worry about)." - Credit to [mdaffin](https://www.reddit.com/user/mdaffin/)

##### Ok that's cool but why can't I edit the other files?
 You Can. Should you? It depends. Here are some common use cases laid out below:
 
| Use Case | Edit files besides .md files? |
| ------ | ------ |
| Editing page data | No |
| Adding a new page | No |
| Deleting a page | No |
| Adding media to a page (picture, video, etc.) | Depends on Theme |
| Changing Navigaton Bar, Site Colors, or Site Layout | Depends on Theme |

##### What does "Depends on Theme Mean?"

Every Hugo Site is built with a theme. The theme dictates site layout, and where and how your content will be stored. It also determines the look and feel of the site, and some the really nice themes have cute little forms and "contact me" buttons embedded inside. It is imperative you chose a good, easily editable, highly configurable theme. This site uses a modified version of the "Hugo Serif Theme". If your theme was made a company, or a team of people, chances are it is a lot easier to customize, and will require little to no html or css changes. If your theme was made by a lone wolf developer, or a sleep deprived student moonlighting as a web developer, then chances are the theme has not taken into account many use cases, and is not easily customizable. Very few themes have the flexibility required to adapt into a landing page, blog, or portfolio. So Hugo works around this by providing themes designed on what content your site will store. So you pick a blog theme for a personal blog, or a resume theme for an online portfolio, instead of frantically trying to change things to fit. Pick the right theme for your site. It will save you a lot of hassle. 
##### Oh ok, so what about this site? If I wanted to add a new page, or add a new team member, would I have to change the html or css in the theme?

No. The people at [zerostatic](www.zerostatic.io) make wonderful themes that allow for easy user customization. The only CSS and HTML I had to change was to make the color Red and to change the font. 

##### Ok how do I get started changing things on this site (or on a fork of this site)?

The majority of the configuration settings will be found in the "config.toml" and the index.md files. The "features.json" file will also be pretty helpful.

### Cloning and Running Locally

Want to do something similar! Great! Go read the Hugo Quickstart Guide, and get cracking!

### Note to Self from Jason

- Download the extended verison of Hugo when testing locally and use command "hugo server"
- Config.toml has the configuration for the top nav bar, refer to pages with same name as the content markdown
- In the content folder .md files, remove any "main" attributes (use the config.toml instead with weight)
- Change the themes/hugo-serif-themes/layouts/index.html because the config.toml nav bar doesn't affect the home page
- TODO: find out why css doesn't work for home page on local

License
----

MIT


**Free Software, Hell Yeah!**
