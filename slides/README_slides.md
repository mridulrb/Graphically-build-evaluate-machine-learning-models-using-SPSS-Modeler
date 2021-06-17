---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: myst
      format_version: '1.1'
      jupytext_version: 1.1.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---
<!-- 
+++ {"slideshow": {"slide_type": "slide"}}

# Tutorial slides

- Slides are optional (e.g., you may not use them if your presentation is via live coding).
- If the pre-recorded presentations will use slides, we request that you deposit the slides in this folder.

+++ {"slideshow": {"slide_type": "slide"}}

## Use text-based source

- We ask that you use text-based formats for your slides, e.g., markdown 
- This markdown file is an example source for slides using `nbconvert` and Reveal. See the GitHub action '.github/workflows/slides.yml' in this repo so see how this markdown file is converted to a HTML slide show and published on GitHub Pages - https://fawazsiddiqi.github.io/slides_to_pages

+++ {"slideshow": {"slide_type": "subslide"}}

## An example sub-slide

- Another option: you can write your slide content using markdown and use an app for slide design, like [Deckset](https://www.deckset.com) or similar.

+++ {"slideshow": {"slide_type": "slide"}}

## Naming convention and file list

- Use a **naming convention** where each file name starts with a number, reflecting the order of use in the presentation of the tutorial.
- List your slide files in a markdown, with a brief description.


+++ {"slideshow": {"slide_type": "slide"}} 
-->


**🌟 Overview** <br />
In this workshop, we will explain how to graphically build and evaluate machine learning models by using the SPSS Modeler flow feature in IBM® Watson™ Studio. IBM Watson SPSS Modeler flows in Watson Studio provide an interactive environment for quickly building machine learning pipelines that flow data from ingestion to transformation to model building and evaluation, without needing any code. This workshop introduces the SPSS Modeler components and explains how you can use them to build, test, evaluate, and deploy models!🤩

🎓 What will you learn? <br />
- How to create an SPSS Modeler flow
- How to use the SPSS tool to profile and analyze data
- How to train a machine learning model with SPSS and evaluate the results

👩‍💻 Who should attend? <br />
All Developers interested in machine learning and data science are welcome to attend the webinar!

+++ {"slideshow": {"slide_type": "subslide"}}

🎙️ Speakers <br />
- Mostafa Abdelaleem, IBM Developer Advocate, Egypt - https://www.linkedin.com/in/mostafa-abdelaleem/
- Mridul Bhandari, IBM Developer Advocate, U.A.E - https://www.linkedin.com/in/mridul-bhandari

🎈 Prerequisites <br />
☁ Register for a free IBM Cloud Account: https://ibm.biz/DeveloperSummit

🍉 Register for the live stream: <br/>
https://virtual.eventtus.com/xongbf6b80wcfsbn7ah8mlm1whj7nrzw/backstage/zxjqqqkzxpk3lbgxjyg7scjf6iklo0ze

👩‍💻Resources <br />
- GitHub Repository - https://ibm.biz/DeveloperSummit-SPSSRepo
- Workshop Slides - https://ibm.biz/DeveloperSummit-SPSSSlides
- Survey - https://ibm.biz/DeveloperSummit-Survey
- Meetup page - https://www.meetup.com/IBM-Cloud-MEA/events/ 

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide1.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide2.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide3.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide4.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide5.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide6.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide7.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide8.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide9.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide10.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide11.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide12.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide13.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide14.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide15.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Graphically-build-evaluate-machine-learning-models-using-SPSS-Modeler/blob/main/images/slide_images/Slide16.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

## License

**Recommend** that slides be shared under a [CC-BY](https://creativecommons.org/licenses/by/4.0/) license.
