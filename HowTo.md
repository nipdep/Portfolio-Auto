---
layout: post
title: "How To Build you Portfolio"
description: 'Innovate, Create, Repeat: My Project Journey'
image: assets/images/pic01.jpg
nav-menu: true
show_tile: false
order: 6
---
Here you are looking for a easier way to build your portfolio...
Sweat no more!
This project has made it much easier to do it than you thnk.
Follow along with me.

# Home page

#### Site description and Landing Title
![Alt text](image-3.png)
As you have checkout the portfolio already, the very first thing you saw was the home page. It is the first thing whoever visits your portfolio sees. So obviously it has to look good and catchy.

To do any changes to the home of your portfolio, head to index.md in the root of your application.
The home page was generated from the index.md file.
There you can see the front matter(the part betweeen tripe-dashed lines) as follows

```
---
layout: home
title: Home
landing-title: "Hi, I'm WhoEver"
description: null
image: null
author: null
show_tile: false
---
```

We can change the values that are next to colons(:),....but for now let's change only landing-title variable.

Ofcourse we can put anything to show in large bold letters when the site loads but for now let us stick to changing "I'm Whoever" to "I'm your-name".


To  change the description that is shown under the landing -title can be changed by chnaging descrption variable of the config.yml file.

#### Site Title and Subtitle
![Alt text](image-2.png)

To change this site title and subtitle head to personal.md front matter. There we can see

```
title: Personal
subtitle: Portfolio
```
Change it however you like.

# Personal Information

```
title: Personal
subtitle: Portfolio
email: my.email@gmail.com
description: 'portfolio description'
baseurl: "/forty-jekyll-theme" # the subpath of your site, e.g. /blog
url: # the base hostname & protocol for your site
author:
street_address:
city: 'NY'
state: 
zip_code: 
country: 'USA'
phone: '+0000000'
```

The info that are shown in the bottom of the home page as the personal info such as email address, phne number, address can be changed in the personal.md file front matter.

![Alt text](image-5.png)

# Pubications

The posts under the publications folder is shown here.
In the front matter of the publications.md we can change the decrption and the image to customize the web page.

Under publications folder there is the template file in markdown.
Customizing it accoriding to my needs is really easy.
First I have to create a copy of the template file and change the data accordingly.

OK. That's really easy. But what if I have two or more publcations to show as a seperate page? Just do the same procedure..duplicate the publications template or the page you created and change the details inside it as accordingly.

The template cosists of basic info that we need to include such as
  - abstract
  - Key information
  - Lessons learned


# Archievements
Same as above. Create your own pages from the tempate that is avalable.

Here we can customize 
  - Basic info about the achievement
  - Description
  - Technologies and Methodologies used

# Experiences
Yes...You guessed it correct. Same procedure. And don't forget to remove the template file from the folder otherwise it would show up in our site.

This page template consists of following areas to fill

  - Basic info such as the company, job title, time period..etc
  - Description
  - Collaborated Projects

# Projects
Same boring procedure to create the pages.

And we got the space to fill
  - Basc info about project such as status, tye, area, link to the code...
  - Description
  - Features
  - Technologies
  - Methodologies
  - Project Visualization
  - Lessons Learned

# Personal Info page

To change the personal info page which is depicted in the "Who am I" tile, we have change the details in the persoanl.md
Oh these templates are making my life easier.
It already got the fields
 - Myself
 - A space to describe my self and
 - Fields of Interest
 - Soft Skills
 - Certificates


# All done?

Now we are ready to see how  the final product looks like. You

In the terminal run

```
bundle exec run jekyll
```

And our page will be visible in the [link](http://127.0.0.1:4000/forty-jekyll-theme/)