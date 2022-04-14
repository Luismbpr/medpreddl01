# Project: medpreds06

***

## Table of Contents

* [About Project General](#about-project)
* [Project General Procedure](#project-general-procedure)
* [Project Information](#project-information)
* [List of Diseases](#list-of-diseases)
* [Multiple Project Description](#multiple-project-description)
* [Project Deployment](#project-deployment)
* [Dataset Information](#dataset-information)
* [Languages Used](#languages-used)
* [Other Resources](#other-resources)
* [Other Information](#other-information)

***
## About Project
<p> Creation and deployment of an application that predicts whether a set of inputs correspond or not to a disease.</p>
<p> Project created using ML and DL Models based on different Datasets.</p>

## Project Information
<p> Each dataset used contains different information about users with and without the disease.</p>
<p> Each dataset used a different technique to gather the information.</p>
<br>

## Project General Procedure
<ul>
<li><p> Dataset:</p></li>
<ul>
  <li><p> Dataset Acquisition.</p></li>
  <li><p> Dataset Analysis.</p></li>
</ul>
<li><p> Model</:p></li>
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



<!-->
The dataset is comprised of multiple features which are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
The features describe characteristics of the cell nuclei present in the image. [UCI](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).
The dataset contains information about whether those cells were benign or malignant.
<!-->

## List of Diseases
<hr>
<h3> The diseases that this app can predict are the following:</h3>
<ul>
<hr>
<li><p><b>Cancer.</b></p></li>
<li><p><b>Diabetes.</b></p></li>
<li><p><b>Heart.</b></p></li>
<li><p><b>Liver.</b></p></li>
<li><p><b>Kidney.</b></p></li>
<li><p><b>Malaria.</b></p></li>
<li><p><b>Pneumonia.</b></p></li>
</ul>
<hr>

## Dataset Information
<p>Each Dataset contains specific information about the disease.</p>
<p> The sources used for the acquisition of the datasets are the following:</p>

<!--> ------------------------ Cancer Start - Done  ------------------------ <!-->
<ul>
<li><p>Cancer Dataset Information</p></li>
</ul>

* Taken from: [UCI](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

* For more information about cancer please visit: [cancer.net](https://www.cancer.net/)).

- Sources:
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>

<!--> ------------------------ Cancer End - Done ------------------------ <!-->

<!--> ------------------------ Diabetes Start - Done  ------------------------ <!-->
<ul>
<li><p>Diabetes Dataset Information</p></li>
</ul>

* Taken from: [NIDDK](https://www.niddk.nih.gov/health-information/diabetes/)).
* Dataset also located on: [Kaggle](https://www.kaggle.com/mathchi/diabetes-data-set)).

* For more information about diabetes please visit the following websites:
* [cdc.gov](https://www.cdc.gov/diabetes/index.html)).
* [diabetes.org](https://www.diabetes.org/)).

- Sources:
- <i>Donor of database: Vincent Sigillito (vgs@aplcen.apl.jhu.edu) Research Center, RMI Group Leader Applied Physics Laboratory The Johns Hopkins University Johns Hopkins Road Laurel, MD 20707 (301) 953-6231.</i>
- <i>(NIDDK) National Institute of Diabetes and Digestive and Kidney Diseases</i>

<!--> ------------------------ Diabetes End - Done ------------------------ <!-->

<!--> ------------------------ Heart Start - Done ------------------------ <!-->
<ul>
<li><p>Heart Disease Dataset Information</p></li>
</ul>

* Taken from: [UCI](https://archive.ics.uci.edu/ml/datasets/heart+disease)).

* For more information about heart disease please visit the following websites:
* [cdc.gov](https://www.cdc.gov/heartdisease/index.htm)).
* [heart.org](https://www.heart.org/)).

- Sources:
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/heart+disease" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>
<!--> ------------------------ Heart End - Done ------------------------ <!-->

<!--> ------------------------ Kidney Start - Done ------------------------ <!-->
<ul>
<li><p>Kidney Disease Dataset Information</p></li>
</ul>

* Taken from: [UCI](https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease)).

* For more information kidney disease please visit the following websites:
* [NIDDK](https://www.niddk.nih.gov/health-information/kidney-disease/chronic-kidney-disease-ckd/what-is-chronic-kidney-disease#symptoms)).

- Sources:
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/chronic_kidney_disease" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>

<!--> ------------------------ Kidney End - Done ------------------------ <!-->

<!--> ------------------------ Liver Start - Done ------------------------ <!-->
<ul>
<li><p>Liver Disease Dataset Information</p></li>
</ul>

* Taken from: [UCI](https://archive.ics.uci.edu/ml/datasets/ILPD+%28Indian+Liver+Patient+Dataset%29#).

* For more information about liver disease please visit the following websites:
* [liverfoundation.org](https://liverfoundation.org/)).
* [mayoclinic.org](https://www.mayoclinic.org/diseases-conditions/liver-problems/symptoms-causes/syc-20374502)).
* [cleveland.org](https://my.clevelandclinic.org/health/diseases/17179-liver-disease)).

- Sources:
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/ILPD+%28Indian+Liver+Patient+Dataset%29#)" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>

<!--> ------------------------ Liver End - Done ------------------------ <!-->
<!--> ------------------------ Malaria Start - Done ------------------------ <!-->
<ul>
<li><p>Malaria Dataset Information</p></li>
</ul>

* Taken from: [LHNCBC](https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malaria-datasets).
* Dataset also located on: [Kaggle]("https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria").

* For more information about liver disease please visit the following websites:
* [NIDDK](https://www.niddk.nih.gov/health-information/kidney-disease/chronic-kidney-disease-ckd/what-is-chronic-kidney-disease#symptoms)).
* [cdc.gov](https://www.cdc.gov/malaria/about/disease.html)).
* [mayoclinic.org](https://www.mayoclinic.org/diseases-conditions/malaria/symptoms-causes/syc-20351184)).

- Sources:
- <i>National Library of Medicine Lister Hill National Center for Biomedical Communications. <a href="https://lhncbc.nlm.nih.gov/LHC-downloads/downloads.html#malaria-datasets" target="https://lhncbc.nlm.nih.gov/"> LHNCBC</a>.</i>

<!--> ------------------------ Malaria End  - Done ------------------------ <!-->

<!--> ------------------------ Pneumonia Start ------------------------ <!-->
<ul>
<li><p> Pneumonia Dataset Information</p></li>
</ul>

* Taken from: [data.mendeley.com](https://data.mendeley.com/datasets/rscbjbr9sj/2)
* Dataset also located on:
* [cell.com](ttps://www.cell.com/cell/fulltext/S0092-8674(18)30154-5).
* [Kaggle]("https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria").

* For more information about pneumonia please visit the following websites:
* [NIDDK](https://www.niddk.nih.gov/health-information/kidney-disease/chronic-kidney-disease-ckd/what-is-chronic-kidney-disease#symptoms)).
* [lung.org](https://www.lung.org/lung-health-diseases/lung-disease-lookup/pneumonia/)).
* [cdc.gov](https://www.cdc.gov/pneumonia/causes.html)).

- Sources:
- Kermany, Daniel; Zhang, Kang; Goldbaum, Michael (2018), “Labeled Optical Coherence Tomography (OCT) and Chest X-Ray Images for Classification”, Mendeley Data, V2, doi: 10.17632/rscbjbr9sj.2
- <i>Dua, D. and Graff, C. (2019). Irvine, CA: University of California, School of Information and Computer Science. <a href="https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)" target="http://archive.ics.uci.edu/ml"> UCI Machine Learning Repository</a>.</i>

<!--> ------------------------ Pneumonia End ------------------------ <!-->

<!--> --------------------------------------------------------------- <!-->

### Project Deployment
* [Project Located on Github](https://github.com/Luismbpr/medpreddl01).
* [Project deployed on Heroku Cloud](https://medpreddl01.herokuapp.com/).

***
<br>
## Different languages and resources where used in order for this application to be deployed.
<br>
## Languages Used
<br>
<ul>
<li> * Python </li>
<br>
<ul>
<li><p> Data Analysis.</p></li>
<br>
<li><p> Model Creation.</p></li>
<br>
<li><p> Model Deployment.</p></li>
<br>
</ul>

<li> * HTML and CSS </li>
<br>
<ul>
<li><p> Website - Front-End for model deployment.</p></li>
<br>
</ul>
</ul>

## Other Resources
<ul>
<li><p> Flask.</p></li>
<li><p> Gunicorn.</p></li>
<li><p> Heroku.</p></li>
<br>
</ul>
<br>

## Other Information
<p>Medical Web App based on: </p>
<p>The model creation decision was done taking in consideration various factors, some of them involving the app deployment on the web.</p>
<br>
- Based on Shobhit Srivastava's and Karan mehra's <a href="https://github.com/shobhitsrivastava-ds/ML-MT-WebApp" target="_blank">Project</a>
<br>

## Notes:
<br>
<p>This project was not endorsed by any company.</p>
<p> The application and information displayed here is for educational purposes and will have some prediction errors. This should not be taken as medical advice.</p>
<p> For questions go with your medical advisor.</p>




***
