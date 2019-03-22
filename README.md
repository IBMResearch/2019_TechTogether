# 2019 TechTogether Workshop Tutorial
This repository includes the IBM Research 2019 TechTogether Workshop and tutorial information.

The workshop is scheduled for Friday evening, March 22, 2019.  The workshop will go through most of the steps outlined in the tutorial.

## IBM Research Challenge: 
### Trusted AI: making AI safer and more fair

Develop and demo an AI application that is fair, and inspires confidence. You can use IBM's open source AI toolkits for fairness and robustness, and Watson Studio deep learning tools. The winning team will produce a creative AI application that people can trust.


## Tutorial
This tutorial will show the 2019 TechTogether hackathon participants how to do the following:
1) Create an IBMid and an IBM Cloud account.
2) Board the IBM Research premium IBM Cloud account.
3) Create a Deep Learning IBM Watson Studio project.
4) Create and run an a Jupyter notebook example in the IBM Watson Studio project using IBM Watson Machine Learning.

Use the PDF slides to go through the tutorial on your own or the PDF slides and videos together.
* [PDF Slides](https://github.com/IBMResearch/2019_TechTogether/blob/master/TechTogether_MNIST_Demo.pptx)

### Tutorial Videos
1) [Create an IBM Cloud account](https://youtu.be/5Z1T-etUCZc)
2) [Create an IBM Watson Studio project](https://youtu.be/V3iROjBi-T4)
3) [Create and run the Jupyter notebook example](https://youtu.be/m4o0R_G-GOc)

## Using the AI Fairness 360 Open Source Toolkit in Watson Studio
This extensible open source [toolkit](http://aif360.mybluemix.net) can help you examine, report, and mitigate discrimination and bias in machine learning models throughout the AI application lifecycle. Containing over 70 fairness metrics and 10 state-of-the-art bias mitigation algorithms developed by the research community, it is designed to translate algorithmic research from the lab into the actual practice of domains as wide-ranging as finance, human capital management, healthcare, and education.

The [Bias in Image based Automatic Gender Classification](https://github.com/IBMResearch/2019_TechTogether/blob/master/Tutorial_Gender_Classification_example.ipynb) Jupyter notebook was modified to run in Watson Studio.  It is based on the original AIF360 [notebook](https://nbviewer.jupyter.org/github/IBM/AIF360/blob/master/examples/tutorial_gender_classification.ipynb) example.

### How to use
1) [Create an IBM Cloud account](https://youtu.be/5Z1T-etUCZc)
2) [Create an IBM Watson Studio project](https://youtu.be/V3iROjBi-T4)
3) Open the Cloud object storage service instance and create a bucket called utkface
4) Download the [UTKFace](https://susanqq.github.io/UTKFace/) aligned and cropped images [dataset](https://drive.google.com/drive/folders/0BxYys69jI14kU0I1YUQyY1ZDRUE)
5) Upload the crop_part1.tar.gz into the utkface bucket
5) Open the Watson Studio project created in step #2 and add a new notebook to the project.
6) Download the [Bias in Image based Automatic Gender Classification](https://github.com/IBMResearch/2019_TechTogether/blob/master/Tutorial_Gender_Classification_example.ipynb) notebook and then use the import notebook function from the Watson Studio notebook.
7) Update the ``` COS_API_KEY_ID = "***", COS_AUTH_ENDPOINT = "***" COS_RESOURCE_CRN = "***" ``` values in the notebook with the appropriate values for your cloud object storage instance.
8) Run through the steps in the notebook
