# **hw1-horiseon-seo**

## **The Goal**
The goal of this project was to refactor the Horiseon website by ensuring all files/code met accessibility standards for optimal search engine optimization.

## **Changes Made**
I was able to do this by replacing many of the redundant syntax in the style.css file such as the unecessary img, h3, and paragraph selectors that were in the `<div class="content">`. 

![all the changes made to syntax in style.css](/desktop/Projects/Homework/hw1-horiseon-seo/readme_sc/Article.png/)

I also fixed the `<a href="#search-engine-optimization">Search Engine Optimization</a>` link by adding the missing id tag to the first article of the `<div class="content">`.

## **Overall Thoughts**
Throughout this assignment I feel like I've grown more accustomed to the proper layout of an html and css file. I was also able to get some practice with debugging in here, although I don't think that it was part of the actual project.  







Homework #1: The search engine optimization of Horiseon

I first replaced all of the unecessary img selectors in the style.css file and replaced it with an image class. see line 164.

I then replaced all of the unessary h2 lines of code in the style.css file with a single line of code. I did this by giving all the h2 tags in the index.html file besides the footer a class of "ph2" which stands for paragraph heading 2s.

fixed seo in html link. (nav bar)

added a id tag to the Search Engine Optimization so the link would correctley work

deleted the unecessary h3 lines of code in the style.css file and replaced them with just the h3 because they all had the same modifications. It didn't make sense to have three things that serve the same purpose when you're able to just use one simple h3 tag instead.

deleted and replaced the three img tag lines of code in the style.css file and replaced them with one img line of code and added the max-height: 200px; into it. I also deleted the max-width: 150px; because it wasn't needed.

deleted the unecessary classes in the index.html file for search-engine-optimization, online-reputation-managment and social-media-marketing and replaced it with a single class of class="mainp" which stands for main paragraph.

added alts to the images under the benefits div.