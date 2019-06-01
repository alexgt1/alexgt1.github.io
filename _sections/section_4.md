---
section_number: 04
section_title: 1. Understanding Jekyll and Deploying my Server

---

Today I began working with Jekyll. I had used prebuilt Jekyll themes in the past for Project 1 and Software Engineering but seeing as I was building this site from the ground up I thought it would be a good idea to get a proper understanding of Jekyll and how it varies from other web technologies. 

Below are a few key take aways I thought were interesting, these help to distinguish Jekyll from your basic HTML or Wordpress based sites.

### What is Jekyll?
Jekyll is a static site generator. It is actively maintained and has the largest community of all the static site generators.

### What is a static site generator?
A static site generator takes source files and generates an entirely static website. Static sites such as Jekyll are extremely fast as the web server only needs to return a file. This is a lot different to a wordpress site for example which has to build a whole page from scratch on every request. This is tedious and involves putting together all the template files and getting any content or data from the database. This is made worse if the site is using plugins as well.


### Security
Not only are Jekyll sites fast but because there are only static files on the server there's nothing dynamic that can be exploited. Therefore the risk of your site being hacked is greatly reduced. 


### Version control. 
All the source code for our Jekyll site can live in a version control system such as Git. With Git we can go back to any single version of the site in its entire history, this also servers as an offsite backup, if we ever need to restore a server all of the files we need to restore are in the git repository. 


## Setting up my Jekyll Server

To set up Jekyll I used:

    Jekyll Serve

This command built my site and created a second version in the _site directory. This allows me to run the website locally on a development server making it easy to see changes.


**I found this video useful for setting up my Jekyll site**

<iframe width="560" height="315" src="https://www.youtube.com/embed/NJU1wluNrBw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>