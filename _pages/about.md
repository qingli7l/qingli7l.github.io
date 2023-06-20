---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Qing Li received the Ph.D. degree in computer science from the Chongqing University of Posts and Telecommunications and under a joint project in the Chongqing Institute of Green and Intelligent Technology, Chinese Academy of Sciences. To further study deep learning and image processing, she had a one-year [internship](http://www.nlpr.ia.ac.cn/pal/People/LiQing.html) in the National Laboratory of Pattern Recognition of the Institute of Automation, Chinese Academy of Sciences. Her current research interests include big data mining and analysis, evolutionary computing, deep learning, in which she has published papers in SCI Information Sciences, Journal of Big Data, CCF SMC, and IEEE ICCSN, etc. She obtained national invention patent authorizations, participated in several national projects, and served as a reviewer for many important journals and conferences such as IEEE/CAA Neurocomputing, JAS, CCF SMC, etc.  


Education
======
* Doctor of Engineering (2019/09 ~ 2023/06)
  * University of Chinese Academy of Sciences and Chongqing University of Posts and Telecommunications
  * Joint Training in Chongqing Institute of Green and Intelligent Technology, Chinese Academy of Sciences
    * Computer Science and Technology
    * Pattern Recognition and Image Processing
* Master of Engineering (2016/09 ~ 2019/06)
  * University of Chinese Academy of Sciences
    * Computer Application Technology
    * Pattern Recognition and Machine Learning
* Bachelor of Engineering (2012/09 ~ 2016/06)
  * Sichuan Normal University
    * Digital Media Technology
    * Virtual Reality


Publications
======
1. Q. Li, M. S. Shang, “[An Efficient Annealing-Assisted Differential Evolution for Multi-parameter Adaptive Latent Factor Analysis](https://link.springer.com/article/10.1186/s40537-022-00638-8)”, Journal of Big Data, 2022.
2. Q. Li, D. W. Xiong, M. S. Shang, “[Adjusted Stochastic Gradient Descent for Latent Factor Analysis](https://www.sciencedirect.com/science/article/pii/S0020025521012871)”, Information Sciences, 588, pp. 196-213, 2022.
3. Q. Li, M. S. Shang, “[BALFA: A Brain Storm Optimization-based Adaptive Latent Factor Analysis Model](https://www.sciencedirect.com/science/article/abs/pii/S0020025521008653)”, Information Sciences, 578, pp. 913-929, 2021.
4. Q. Li and M. Shang, “[A Compressed Sensing and Porous 9-7 Wavelet Transform-based Image Fusion Algorithm](https://ieeexplore.ieee.org/document/9283284/),” 2020 IEEE International Conference on Systems, Man, and Cybernetics (SMC), Toronto, ON, 2020, pp. 4185-4191, doi: 10.1109/SMC42975.2020.9283284.
5. L. M. Zhou, Q. Li, M. S. Shang, “Chronic Disease Detection via Non-negative Latent Feature Analysis”, IEEE International Conference on Networking, Sensing and Control, 2021.

Patents
======
1. Nengfeng Zhang, Qing Li, Xin Luo, “An Alzheimer's disease detection device based on support vector machines.” CN112155550A, 2021.

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
