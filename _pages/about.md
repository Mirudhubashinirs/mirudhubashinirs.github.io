---
permalink: /
# title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<!--
This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the repository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. Incidentally, these same features make it a great template for anyone that needs to show off a professional template!

 You can fork [this template](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and Markdown files, add your own PDFs and other content, and have your own site for free, with no ads!

# data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, Academic Pages makes you separate the website's content from its form. The content & metadata of your website are in structured Markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various Markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your Markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over - just be sure to save the Markdown files! You can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

For those users that need more advanced functionality, the template also supports the following popular tools:
- [MathJax](https://www.mathjax.org/) for mathematical equations
- [Mermaid](https://mermaid.js.org/) for diagraming
- [Plotly](https://plotly.com/javascript/) for plotting

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](https://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
-->
I am an Embedded AI and Machine Learning Engineer with a Master’s degree in Embedded Systems Engineering from Fachhochschule Dortmund, Germany. My work focuses on building practical, data-driven AI solutions for embedded, edge, and real-time systems.

I have hands-on experience in machine learning, computer vision, and data pipelines, with projects spanning automotive embedded systems, edge AI, and cloud-integrated applications. My Master’s thesis at Aptiv involved designing and deploying a LightGBM-based model for real-time thermal prediction and energy management on MCU-based automotive ECUs, optimized under hardware constraints.

I have also worked on computer vision pipelines using YOLOv8 and PyTorch, deploying models on Triton Inference Server and analyzing CPU vs GPU performance on NVIDIA Jetson platforms. My projects include NLP-based chatbots, autonomous vehicle simulation, predictive analytics, and API-based AI services.

I enjoy working at the intersection of embedded systems, AI, and software engineering, and I am particularly interested in data engineering for AI, edge intelligence, and applied machine learning in real-world systems.


## Projects 

<section class="projects">

<!-- Project: Embedded Neural Network for Thermal Prediction -->
<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border-radius:10px; background:#f5f5f5;">
  <h3 style="margin:0 0 0.3rem 0;">
    Embedded Neural Network for Real-Time Thermal Prediction and Energy Management
  </h3>
  <p style="margin:0 0 1rem 0; font-size:0.95em; color:#666;">
    Aptiv Services Deutschland GmbH, Wuppertal · July 2024 – March 2025
  </p>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">
      Designed and deployed a machine learning–based thermal prediction and energy management system for MCU-based automotive ECUs, optimized for real-time inference under constrained embedded resources.
    </p>
  </div>
  <div class="project-meta" style="margin-top:0.9rem; display:inline-flex; gap:0.4rem; flex-wrap:wrap;">
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Embedded AI</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Machine Learning</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Automotive ECUs</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">LightGBM</span>
  </div>
</div>

<!-- Project: CPU vs GPU Performance Analysis -->

<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border-radius:10px; background:#f5f5f5;">
  <h3 style="margin:0 0 0.3rem 0;">
    CPU vs GPU Performance Analysis for Real-Time Object Counting
  </h3>
  <p style="margin:0 0 1rem 0; font-size:0.95em; color:#666;">
    Honeywell, Lotte · October 2023 – March 2024
  </p>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">
      Built and evaluated a computer vision pipeline for real-time object detection and counting, deployed using Triton Inference Server and benchmarked on edge hardware platforms.
    </p>
  </div>
  <div class="project-meta" style="margin-top:0.9rem; display:inline-flex; gap:0.4rem; flex-wrap:wrap;">
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Computer Vision</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Edge AI</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">YOLOv8</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">GPU Computing</span>
  </div>
</div>

<!-- Project: NLP Chatbot -->

<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border-radius:10px; background:#f5f5f5;">
  <h3 style="margin:0 0 0.3rem 0;">
    NLP-Based Chatbot for University Student Enquiries
  </h3>
  <p style="margin:0 0 1rem 0; font-size:0.95em; color:#666;">
    Fachhochschule Dortmund · November 2022 – January 2023
  </p>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">
      Developed an NLP-based chatbot to automate student enquiries related to grades, address updates, and university services using intent recognition and response logic.
    </p>
  </div>
  <div class="project-meta" style="margin-top:0.9rem; display:inline-flex; gap:0.4rem; flex-wrap:wrap;">
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">NLP</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Chatbot</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Machine Learning</span>
  </div>
</div>

<!-- Project: Autonomous Bale-Picking Vehicle -->

<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border-radius:10px; background:#f5f5f5;">
  <h3 style="margin:0 0 0.3rem 0;">
    Autonomous Bale-Picking Vehicle for Precision Farming
  </h3>
  <p style="margin:0 0 1rem 0; font-size:0.95em; color:#666;">
    Fachhochschule Dortmund · April 2022 – July 2022
  </p>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">
      Designed and simulated an autonomous navigation system for a robotic bale-picking vehicle, focusing on vehicle dynamics, control algorithms, and obstacle avoidance.
    </p>
  </div>
  <div class="project-meta" style="margin-top:0.9rem; display:inline-flex; gap:0.4rem; flex-wrap:wrap;">
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Robotics</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Autonomous Systems</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Simulation</span>
  </div>
</div>

<!-- Project: Cloud-Based DC Motor Control -->

<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border-radius:10px; background:#f5f5f5;">
  <h3 style="margin:0 0 0.3rem 0;">
    Cloud-Based Speed Control of DC Motor
  </h3>
  <p style="margin:0 0 1rem 0; font-size:0.95em; color:#666;">
    KG Group, Coimbatore, India · December 2019 – May 2020
  </p>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">
      Developed a cloud-integrated DC motor control system enabling secure remote monitoring and real-time speed control using PWM signals.
    </p>
  </div>
  <div class="project-meta" style="margin-top:0.9rem; display:inline-flex; gap:0.4rem; flex-wrap:wrap;">
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Embedded Systems</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">IoT</span>
    <span style="background:#e0e0e0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Cloud Computing</span>
  </div>
</div>

