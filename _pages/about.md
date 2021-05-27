---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


About Me
======

My name is Guangyu Shen. I am currently a first year Ph.D student at the [Department of Computer Science](https://www.cs.purdue.edu/) at [Purdue University](https://www.purdue.edu/), advised by [Prof. Xiangyu Zhang](https://www.cs.purdue.edu/homes/xyzhang/). My research interests mainly lie at adversarial machine learning and backdoor attacks/defense for AI models. 

I am also a core member of team Perspecta-PurdueRutgers for [TrojAI competition](https://pages.nist.gov/trojai/). Our team ranks top cross round 1 to 4 and 6. Find more info [here](https://pages.nist.gov/trojai/docs/about.html).

News
======
* **May. 2021:** Our paper on backdoor scanning got accetped to [ICML 2021](https://icml.cc/). Full respect to the co-workers!

Publications
======
* **Backdoor Scanning for Deep Neural Networks through K-Arm Optimization** <br>
  **Guangyu Shen***, Yingqi Liu*, Guanhong Tao, Shengwei An, Qiuling Xu, Siyuan Cheng, Shiqing Ma, Xiangyu Zhang <br>
  *Proceedings of the 38th International Conference on Machine Learning (**ICML 2021**)* <br>
  [[pdf](https://arxiv.org/abs/2102.05123)] [[cite](https://scholar.googleusercontent.com/scholar.bib?q=info:taS9v2s0r_8J:scholar.google.com/&output=citation&scisdr=CgXFlNsWEPvnt1ZlwpY:AAGBfm0AAAAAYK9g2pZ2J_1p5oRIDqoD2k36r26mqs3-&scisig=AAGBfm0AAAAAYK9g2qlEyrHyklprPgoYiJG86WNXBE3O&scisf=4&ct=citation&cd=-1&hl=en&scfhb=1)]

* **EX-RAY: Distinguishing Injected Backdoor from Natural Features in Neural Networks by Examining Differential Feature Symmetry** <br>
  Yingqi Liu*, **Guangyu Shen***, Guanhong Tao, Zhenting Wang, Shiqing Ma, Xiangyu Zhang <br>
  *ArXiv. Prepaint 2021* <br>
  [[pdf](https://arxiv.org/abs/2103.08820)] [[cite](https://scholar.googleusercontent.com/scholar.bib?q=info:NbTRUraSRdgJ:scholar.google.com/&output=citation&scisdr=CgXFlNsWEPvnt1Zk7y8:AAGBfm0AAAAAYK9h9y_xAmVEh3rNqOXT5CeuGJRChU7c&scisig=AAGBfm0AAAAAYK9h96v_AM8CHHJY120ySK2RIpsmIli0&scisf=4&ct=citation&cd=-1&hl=en)]
 
 
* **Fooling Semantic Segmentation in One Step via Manipulating Nuisance Factors** <br>
  **Guangyu Shen**, Chengzhi Mao, Junfeng Yang, Baishakhi Ray <br>
  *ECCV 2020 Workshop on Adverasrial Robustness in the Real World* <br>
  [[pdf](http://www.cs.columbia.edu/~junfeng/papers/advspade-eccv20-arow.pdf)][[cite](https://scholar.googleusercontent.com/scholar.bib?q=info:2e2b8XXLw4QJ:scholar.google.com/&output=citation&scisdr=CgXFlNsWEPvnt1ZmZrQ:AAGBfm0AAAAAYK9jfrQkV2GM1lxqS17mmwJ_YsQ8dN_8&scisig=AAGBfm0AAAAAYK9jfn8EYvYjLRRQdQ-jMJAERy0nMAnS&scisf=4&ct=citation&cd=-1&hl=en)][[Conference page](https://eccv20-adv-workshop.github.io/)]

* **PENet: Object Detection using Points Estimation in Aerial Images** <br>
  Ziyang Tang, Xiang Liu, **Guangyu Shen**, Baijian Yang

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
