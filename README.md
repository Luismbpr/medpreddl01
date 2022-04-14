# Project: medpreds06

***

## Table of Contents

* [About](#about)
* [Project Procedure](#project-procedure)
* [List of Diseases](#list-of-diseases)
* [Dataset Information](#dataset-information)
* [Project Deployment](#project-deployment)
* [Resources](#resources)
* [Languages Used](#languages-used)
* [Other Resources](#other-resources)
* [Other Information](#other-information)
* [Notes](#notes)

***
## About
<p> Creation and deployment of an application that predicts whether a set of inputs correspond or not to a disease.</p>
<p> This project was created using ML and DL Models based on different disease datasets acquired from different sources.</p>

* [Back to Table of Contents](#table-of-contents)

## Project Procedure
<ul>
<li><p> Dataset:</p></li>
<ul>
  <li><p> Dataset Acquisition.</p></li>
  <li><p> Dataset Analysis.</p></li>
</ul>
<li><p> Model:</p></li>
<ul>
  <li><p> Model Creation.</p></li>
  <li><p> Model Testing.</p></li>
  <li><p> Model Deployment.</p></li>
</ul>
<li><p> Application:</p></li>
<ul>
  <li><p> Application Creation.</p></li>
  <li><p> Application Testing (Local and External).</p></li>
  <li><p> Application Modification (Local and External).</p></li>
  <li><p> Application Deployment (Local and External).</p></li>
</ul>
<li><p> Documentation:</p></li>
<ul>
  <li><p> Creation of Required Documentation.</p></li>
</ul>
</ul>
<br>

* [Back to Table of Contents](#table-of-contents)

## List of Diseases
<hr>
<h4> The diseases that this app can predict are the following:</h4>
<ul>
<hr>
<li><p><b>Cancer.</b></p></li>
<li><p><b>Diabetes.</b></p></li>
<li><p><b>Heart Disease.</b></p></li>
<li><p><b>Liver Disease.</b></p></li>
<li><p><b>Kidney Disease.</b></p></li>
<li><p><b>Malaria.</b></p></li>
<li><p><b>Pneumonia.</b></p></li>
</ul>

* [Back to Table of Contents](#table-of-contents)

<hr>

## Dataset Information
<p> The information for the acquisition of each disease was gathered by different entities and with different methods.</p>
<p> Each Dataset contains specific information and whether a user has or not the disease.</p>
<p> The sources used for the acquisition of the datasets are the following</p>

***
<h4> Cancer Dataset Information</h4>

* Taken from: [UCI](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

* For more information about cancer please visit: [cancer.net](https://www.cancer.net/)).

- Sources:
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>

* [Back to Table of Contents](#table-of-contents)

***
<h4> Diabetes Dataset Information</h4>

* Taken from: [NIDDK](https://www.niddk.nih.gov/health-information/diabetes/).

* Dataset also located on: [Kaggle](https://www.kaggle.com/mathchi/diabetes-data-set).

* For more information about diabetes please visit the following websites:
* [cdc.gov](https://www.cdc.gov/diabetes/index.html).
* [diabetes.org](https://www.diabetes.org/).

- Sources:
- <i>Donor of database: Vincent Sigillito (vgs@aplcen.apl.jhu.edu) Research Center, RMI Group Leader Applied Physics Laboratory The Johns Hopkins University Johns Hopkins Road Laurel, MD 20707 (301) 953-6231.</i>
- <i>(NIDDK) National Institute of Diabetes and Digestive and Kidney Diseases</i>

* [Back to Table of Contents](#table-of-contents)

***
<h4> Heart Disease Dataset Information</h4>

* Taken from: [UCI](https://archive.ics.uci.edu/ml/datasets/heart+disease).

* For more information about heart disease please visit the following websites:
* [cdc.gov](https://www.cdc.gov/heartdisease/index.htm).
* [heart.org](https://www.heart.org/).

- Sources:
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/heart+disease" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>

* [Back to Table of Contents](#table-of-contents)
***
<h4> Kidney Disease Dataset Information</h4>

* Taken from: [UCI](https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease).

* For more information kidney disease please visit the following websites:
* [NIDDK](https://www.niddk.nih.gov/health-information/kidney-disease/chronic-kidney-disease-ckd/what-is-chronic-kidney-disease#symptoms).

- Sources:
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>

* [Back to Table of Contents](#table-of-contents)

***
<h4> Liver Disease Dataset Information</h4>

* Taken from: [UCI](https://archive.ics.uci.edu/ml/datasets/ILPD+%28Indian+Liver+Patient+Dataset%29#).

* For more information about liver disease please visit the following websites:
* [liverfoundation.org](https://liverfoundation.org/).
* [mayoclinic.org](https://www.mayoclinic.org/diseases-conditions/liver-problems/symptoms-causes/syc-20374502).
* [cleveland.org](https://my.clevelandclinic.org/health/diseases/17179-liver-disease).

- Sources:
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/ILPD+%28Indian+Liver+Patient+Dataset%29#)" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>

* [Back to Table of Contents](#table-of-contents)

***
<h4> Malaria Dataset Information</h4>

* Taken from: [LHNCBC](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malaria-datasets).
* Dataset also located on: [Kaggle]("https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria").

* For more information about malaria please visit the following websites:
* [cdc.gov](https://www.cdc.gov/malaria/about/disease.html).
* [mayoclinic.org](https://www.mayoclinic.org/diseases-conditions/malaria/symptoms-causes/syc-20351184).

- Sources:
- <i>National Library of Medicine Lister Hill National Center for Biomedical Communications. <a href="https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malaria-datasets" target="https://lhncbc.nlm.nih.gov/"> LHNCBC</a>.</i>

* [Back to Table of Contents](#table-of-contents)

***
<h4> Pneumonia Dataset Information</h4>

* Taken from: [data.mendeley.com](https://data.mendeley.com/datasets/rscbjbr9sj/2)
* Dataset also located on:
* [cell.com](https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5).
* [Kaggle]("https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria").

* For more information about pneumonia please visit the following websites:
* [lung.org](https://www.lung.org/lung-health-diseases/lung-disease-lookup/pneumonia/).
* [cdc.gov](https://www.cdc.gov/pneumonia/causes.html).

- Sources:
- Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification”, Mendeley Data, V2, doi: 10.17632/rscbjbr9sj.2

* [Back to Table of Contents](#table-of-contents)

***

## Project Deployment
* [Project Located on Github](https://github.com/Luismbpr/medpreddl01).
* [Project deployed on Heroku Cloud](https://medpreddl01.herokuapp.com/).

***
## Resources
 <p> Different languages and resources where used in order for this application to be deployed. </p>

## Languages Used
<ul>
<h5><li> Python </li></h5>
<ul>
<li><p> Data Analysis.</p></li>
<li><p> Model Creation.</p></li>
<li><p> Model Deployment.</p></li>
</ul>

<h5><li> HTML and CSS </li></h5>
<ul>
<li><p> Website - Front-End for model deployment.</p></li>
</ul>
</ul>

* [Back to Table of Contents](#table-of-contents)
***
## Other Resources
<ul>
<h5><li><p> Flask.</p></li></h5>
<h5><li><p> Gunicorn.</p></li></h5>
<h5><li><p> Heroku.</p></li></h5>
</ul>
<br>

* [Back to Table of Contents](#table-of-contents)
***
## Other Information
<p> Medical Web App based on: </p>
<p>The model creation decision was done taking in consideration various factors, some of them involving the app deployment on the web.</p>
<br>
- Based on Shobhit Srivastava's and Karan Mehra's <a href="https://github.com/shobhitsrivastava-ds/ML-MT-WebApp" target="_blank">Project</a>

- For further inquiries and to see other projects made by me please <a href="https://github.com/Luismbpr/" target="_blank">click here</a>
<br>

* [Back to Table of Contents](#table-of-contents)
***
## Notes
<p> This project was not endorsed by any company.</p>
<p> Special gratitude to all the people who make the datasets and all the information available.</p>
<br>
<hr>
<p> The application and information displayed here is for educational purposes. The accuracy of the models varies and will make some prediction errors. This should not be taken as medical advice.</p>
<p> For further questions about the diseases go with your medical advisor.</p>
<hr>
<!--> When you click here
<sup name="a1">[1](#f1)</sup> <!-->

<!--> It redirects you to here
<b name="f1">1</b> Footnote Content Here [](#a1) <!-->
