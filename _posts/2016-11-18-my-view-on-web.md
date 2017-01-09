---
layout:     post
categories: assignment
title:      "My views on SSG and pre-compiled CSS"
date:       2016-11-30 01:08:44
summary:    In this post I will answer some questions and discuss some topics 
            regarding som basics in client based web development, brought...
---
In this post I will answer some questions and discuss some topics regarding som basics in client based web development, brought to me by course 1dv022 at Lineaus University, Kalmar, Sweden.
----
- **What do you think of pre-compiling your CSS?**
    - **Compare to regular CSS**
    
        *Compared to regular CSS, pre-compiled CSS is very complex. While it's easier to do more extensive changes
        it's much harder to locate errors.*
        
    - **Which techniques did you use?**

        *SASS*
    
    - **Pros and cons?**
    
        **Pros**: *Perform calculations, Nesting, better organization of files and code.*
        
        **Cons**: *Hard to debug, greater complexity*
    
- **What do you think of static site generators?**
    
    *SSG makes it easier to make changes on larger scale of a static website, and therefor also has greater complexity than
    classic HTML/CSS.*
    
    - **What type of projects are they suitable for?**
        
        *Simpler projects, like blogs.*

- **What is robots.txt and how have you configure it for your site?**

    *robot.txt is a file that defines an access policy for web "wanderers/spiders"*
    
    **Content of my robot.txt:**
    
        #Robot.txt file for ...
    
        User-agent: Google
        Disallow:
     
        User-agent: *
        Disallow: /_posts/
    
        Crawl-delay: 1
    
    
- **What is humans.txt and how have you configure it for your site?**
    
    humans.txt is a small file containing some basic info about the people that is running the website.
    
    **Content of my humans.txt:**
    
        /* TEAM */
        	Developer: Emil Thyrell
         	Contact: et222jv@student.lnu.se
         	From: Ljusdal, Gavleborg, Sweden
    
        /* SITE */
    	    Last update: 2016/11/18
    	    Language:  English
    	    Doctype: HTML5/CSS
    	    IDE: WebStorm
    
- *How did you implements comments to blog posts*
    
With DISQUS

- *What is Open Graph and how do you make use of it?*

Open Graph generates stylish links containing data like title, image etc. 
When content from the site which has Open Graph implemented is shared, Open Graph
makes it so that the shared link looks informing and appealing to other people on social
networks.
