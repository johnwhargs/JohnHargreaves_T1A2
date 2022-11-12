# JohnHargreaves_T1A2

## **Assignment** <br>Project: Plan and Develop a Portfolio Website

[Published portfolio website](https://astounding-figolla-7f5c90.netlify.app/ "Netlify deploy") \
[GitHub Repo](https://github.com/johnwhargs/JohnHargreaves_T1A2 "GitHub Repo - JohnHargreaves_T1A2")\
Presentation video

---

## Description and Purpose:

The purpose of my portfolio is to track my current journey at the start of my Full Stack development journey. At the moment I can do HTML and CSS confidently, but as I go along I hope to add further improvements that I will learn throughtout the Coder Academy course.

 Due to contracts with clients I couldn't make it a full design portfolio, but more of an introdution to me as a digital creative.

---

## Sitemap:
![Sitemap made in Milanote](/docs/sitemap.png "Sitemap made in Milanote")
Above is the sitemap of the my portfolio site that I worked to. 

## Procreate Wireframes:
After this sitemap I moved to doodling some rough wireframes in procreate.\
**Wireframe: Landing Page Desktop and Mobile**
![Procreate Wireframe: Landing Page Desktop and Mobile](/docs/Procreate-Wireframe-1.PNG "Procreate Wireframe: Landing Page Desktop and Mobile")

**Wireframe: Blog Templates Desktop and Mobile**
![Procreate Wireframe: Blog Templates Desktop and Mobile](/docs/Procreate-Wireframe-2.PNG "Procreate Wireframe: Blog Templates Desktop and Mobile")

**Wireframe: About Me, Contact, Resume**
![Procreate Wireframe: About Me, Contact, Resume](/docs/Procreate-Wireframe-3.PNG "Procreate Wireframe: About Me, Contact, Resume") 

## Figma Wireframe:
After the doodles in procreate I than recreate text and button components in Figma to use as the base of text and button css styles. I used [Google Material Design's type scale](https://m2.material.io/design/typography/the-type-system.html#type-scale "Google Material Design's type scale") as reference to build the website around.
![Desktop mock up in Figma](/docs/Desktop%20-%201-2.jpg "Desktop mock up in Figma")
Screenshot of the text scale and buttons created in Figma. This influenced the overall design of the website.
![Screenshot of the text scale and buttons created in Figma](/docs/Figma-Components.png "Screenshot of the text styles and buttons created in Figma")

Below is a code snippet of the font families I used in the project.

```
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Overpass:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Piazzolla:ital,opsz,wght@0,8..30,100;0,8..30,200;0,8..30,300;0,8..30,400;0,8..30,500;0,8..30,600;0,8..30,700;0,8..30,800;0,8..30,900;1,8..30,100;1,8..30,200;1,8..30,300;1,8..30,400;1,8..30,500;1,8..30,600;1,8..30,700;1,8..30,800;1,8..30,900&family=Roboto+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&family=Space+Grotesk:wght@300;400;500;600;700&display=swap" rel="stylesheet">

font-family: 'Overpass', sans-serif;
font-family: 'Piazzolla', serif;
font-family: 'Roboto Mono', monospace;
font-family: 'Space Grotesk', sans-serif;
```
Below is a code snippet of some css font styles.
```
    --main-font: 'Overpass', sans-serif;
    --secondary-font: 'Roboto Mono', monospace;

h1{
    font-family: var(--main-font);
    font-weight:300;
    font-size: 6.25rem;
    letter-spacing: -0.09375rem;
    line-height: 7.5rem;
}

h2{
    font-family: var(--main-font);
    font-weight:300;
    font-size: 3.875rem;
    letter-spacing: -0.03125rem;
    line-height: 4.65rem;
    display: block !important;
}

body, li{
    font-family: var(--secondary-font);
    font-weight:normal;
    font-size: 1rem;
    letter-spacing: 0.03125rem;
    line-height: 1.2rem;

}

```

## HTML Documents:
- **index.html**\
This is the landing page of my portfolio. It will contain links to html pages, as well as my socials (LinkedIn, Instagram and GitHub). 

- **about-me.html**\
This page will contain a breif spill about me and my interest.

- **resume.html**\
This page contains my Resume marked up in html and styled using css, as well as an option to download a pdf.

- **blog.html**\
This is a html file with a seperate css stylesheet with custom css used spefically for blogs. A blog template was created to fulfil the five sample posts. Sample blog posts can be found [here](/blog-posts)

- **contact.html**\
This is a html file with a seperate css stylesheet with custom css used spefically for contacts.

## CSS Documents:

- **main.css**\
This css file will contain universal styles, used through out the website.

- **blog.css**\
This css file will contain styles unique to the blog page and templates to for sample posts. I will create a design system to easily style up a blog post. This includes the component of a pulled qoute and a three column image lock-up.

- **landing.css**\
This css file will contain universal styles, used throught out the website.

- **contact.css**\
CSS styles for the contact form.

- **media-query.css**\
Contains all my media quires that make the website responsive to various breaking points.

---


## Functionality / features:

Four components which contain 

---

## Target audience:



