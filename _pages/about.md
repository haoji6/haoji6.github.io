---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi there! I am Haoji Liu, a first-year Ph.D. student in [Systems and Information Engineering](https://engineering.virginia.edu/departments/systems-and-information-engineering) at the [University of Virginia (UVA)](https://www.virginia.edu/), working with Prof. [Byungkyu Brian Park](https://engineering.virginia.edu/faculty/b-brian-park). Prior to UVA, I received my master's degree in Mechanical Engineering from Southeast University, China in 2022. I was with the [Research Center for Intelligent Eletrified Mobility](https://ciem.seu.edu.cn/_s508/main.psp), where I worked with Prof. [Guodong Yin](https://me.seu.edu.cn/ygd/listm.htm) and Associate Prof. [Weichao Zhuang](https://me.seu.edu.cn/zwc1/list.htm). My previous research works focus on vehicle dynamics and control, and cooperative control for connected automated vehicles (CAVs) in mixed traffic.

**Research Bio** | Keywords: connected automated vehicles (CAVs), cooperative driving, eco-driving, mixed traffic. 


My research endeavors to bridge the gap between microscopic vehicle control and macroscopic traffic harmonization. I am interested in leveraging control theory and reinforcement learning techniques to explore how cooperative control of CAVs can transform future transportation systems in terms of safety, efficiency, ecology, and equity. Currently, my research encompasses the following areas: 

1) Cooperative formation and platooning of CAVs in mixed traffic flow; 

2) Cooperative merging of CAVs in mixed traffic; 

3) Cooperative energy-efficient driving for connected vehicles. 

**I'm willing to discuss and collaborate with fellow researchers! Please feel free to reach out via email If you have interesting ideas!**

News
======

* Feb. 2024- Our paper on energy-oriented driving strategy for connected electric vehicles was published in Energy [Online](https://www.sciencedirect.com/science/article/pii/S0360544223033108)
* Feb. 2024- Our paper on eco-routing strategy for vehicles with different powertrain types was accepted by Energy [Online](https://www.sciencedirect.com/science/article/pii/S0360544224003554)
* Nov. 2023- Our paper on eco-routing for electric vehicles using deep reinforcement learning was published in Applied Energy [Online](https://www.sciencedirect.com/science/article/pii/S0306261923010759)
* Oct. 2023- Our paper on traffic-aware ecological cruising control was published in IEEE Transactions on Transportation Electrification [Online](https://ieeexplore.ieee.org/abstract/document/10287643)
* Aug. 2023- Moved to Charlottesville to begin my PhD research journey! 
* Apr. 2023- Our paper on active front steering control considering CAN delay was published in IEEE Transactions on Transportation Electrification [Online](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6687316)
* Feb. 2023- Our paper on cooperative on-ramp merging in mixed traffic was published in IEEE Transactions on Intelligent Transportation Systems [Online](https://ieeexplore.ieee.org/abstract/document/10053376)

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

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

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
