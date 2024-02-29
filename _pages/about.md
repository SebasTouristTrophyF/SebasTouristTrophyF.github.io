---
permalink: /
title: "academicpages is a ready-to-fork GitHub Pages template for academic personal websites"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Starting from May 2021, I worked as a postdoctoral researcher and assistant researcher at the School of Computer Science (School of Software and School of Intelligent Science and Technology) of Sichuan University. From April 2015 to June 2020, I worked as a full-time researcher at Klaustal University of Technology/Lower Saxony Energy Research Center in Germany. Professor Feng Wentao has been engaged in research on computer simulation methods, simulation modeling related to the energy industry, and practical applications of computer simulation in the engineering field. He is also engaged in research on multi view learning and deep learning based simulation modeling of complex physical systems. At present, nearly 30 papers have been published in authoritative international and domestic academic journals and international conferences, including 13 papers indexed by SCI; Publish two academic monographs in English/German; 8 national patents have been applied for, and 3 have been authorized; Responsible for and participated in a total of 12 vertical and horizontal projects at all levels in China and Germany; I am a reviewer for five international authoritative academic journals, including TNNLS.

Publications
======
1.        Shudong Huang, Hongjie Wu, Yazhou Ren, Ivor Tsang, Zenglin Xu, Wentao Feng, Jiancheng Lv, “Multi-view Subspace Clustering on Topological Manifold,” in Proceedings of the Advances in Neural Information Processing Systems 35 (NeurIPS 2022), pp. 1-12, Nov. 2022.

2.        Muhammad Haris, Michael Z. Hou, Wentao Feng, Faisal Mehmood, Ammar b. Saleem, “A regenerative Enhanced Geothermal System for heat and electricity production as well as energy storage,” Renewable Energy, Vol. 197, pp. 342-358, Sep. 2022.

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

