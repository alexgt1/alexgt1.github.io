---
section_number: 08
section_title: Using Collections

---

Collections are a useful way to organize related content in Jekyll. 

The general consensus for using collections is if the things in your collection can be logically grouped and aren't grouped by date (in this case you would use a post instead). 

In total I figured out I would need close to 10 different collections of content across the website. Some of which included the about section, programme section and resource section. 

I defined my collections in the _config.yml file pictured below


    collections:
    	programmes:
    	output: true
    	resources:
    	output: true
    	about:
    	output: true


The items/documents within a collection live in a folder in the root of the site. This folder is named after the specific collection name. e.g. for programmes the folder name would be _programmes

The items in each folder are also written in markdown and can specify variables such as layout and title the same as any other markdown file.

By specifying **output: true** in _config.yml for each collection it means that Jekyll will create a page for each document. 

While this isn't neccessary for every collection it was very useful for the likes of the programme collection as these did require their own page for each programme. 

Pictured: the Programmes collection. I was able to use a control flow statement to display each of the programmes in the Programmes collection in the navigation bar and open each programme in a new page when clicked. 

![Current Site](../collections.PNG)

This video from CloudCannon effectively described how to easily set up collections for your website. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/o7ygmIRgvUA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

