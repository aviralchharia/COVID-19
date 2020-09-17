# COVID-19 Detection Project

The novel Coronavirus also called COVID-19 originated in Wuhan, China in December 2019 and has now spread across the world. It has so far infected around 30 million people and claimed approximately 940,651 lives overall. As the number of cases are rapidly increasing, most of the countries are facing shortage of testing kits and resources. AI is already transforming many different fields. One such field is the area of Medical Diagnosis through accurate clinical computer-aided diagnosis (CAD) systems. The limited quantity of testing kits and increasing number of daily cases encouraged us to come up with a deep learning model that can aid radiologists and clinicians in detecting COVID-19 cases using chest X-rays.

<p align="center">
    <img width="775" height="300" src = 'https://github.com/aviralchharia/COVID-19/blob/master/Detecting%20COVID-19%20with%20Chest%20X-Ray%20Images%20using%20CNN.jpg?raw=true'
</p>


I applied a CNN Model, which I had trained on a COVID-19 Radiography dataset containing Chest X-Rays, for detecting COVID-19 & achieved ~98% accuracy on the validation set with respective to Radiologist's clinical findings. The confusion matrix, the training & validation loss and accuracy curves obtained are as shown below.

<p align="center">
    <img width="300" height="250" src = 'https://github.com/aviralchharia/COVID-19/blob/master/Results%20Obtained/Confusion%20Matrix.png?raw=true'
</p>


<p align="center">
    <img width="350" height="250" src = 'https://github.com/aviralchharia/COVID-19/blob/master/Results%20Obtained/Training%20&%20Validation%20Accuracy.png?raw=true'
</p>
    
    
<p align="center">
    <img width="350" height="250" src = 'https://github.com/aviralchharia/COVID-19/blob/master/Results%20Obtained/Training%20&%20Validation%20Loss.png?raw=true'
</p>
    
Further working on high accuracy multi-class classification of X-Rays for computer-aided diagnosis system which also finds the area of lungs affected by COVID-19.
