---
permalink: /
title: "About Me..."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Howdy! My name is Trevor and I'm an astronomer and planetary scientist from San Antonio, Texas. I'm currently a PhD student at Purdue University in the department of Earth, Atmospheric, Planetary, and Space Sciences studying under Dr. Alexandria Johnson. Before this, I got bachelor's degrees in Physics and Astronomy from the University of Texas at Austin (Hook 'em!) and worked at Southwest Research Institute in my hometown of San Antonio. My interests are in all kinds of planets, those both inside and outside of our solar system, but my expertise is in modeling cloud features around exoplanets! Check out my publications if you want to learn more. I am also a huge proponent of public outreach, and love to organize events. 

Planetary Science
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Atmospheric Physics
======
I started my work in Atmospheric Physics working with Dr. Caroline Morley and post-doc Brianna Lacy while at UT Austin. I worked on a new way to simulate the light scattering of crystaline species like enstatite and forsterite around brown dwarfs. My approach was to use an approximation developed by Min et al. 2005 that could better model spheroids by treating them as coated spheres. This new approach was then integrated into Dr. Lacy's transit spectra code: the Multi-dimensional Exoplanet TransIt Spectra (METIS) model! This code is still under development, and will be released in both Python and Julia when complete! Contact myself or Brianna Lacy for more information!

Teaching and Outreach
======
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

