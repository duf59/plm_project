# plm_project
Practical Machine Learning Course Project

# Description & data

Using devices such as Jawbone Up, Nike FuelBand, and Fitbit it is now possible to collect a large amount of 
data about personal activity relatively inexpensively. These type of devices are part of the quantified self
movement – a group of enthusiasts who take measurements about themselves regularly to improve their
health, to find patterns in their behavior, or because they are tech geeks. One thing that people regularly do
is quantify how much of a particular activity they do, but they rarely quantify how well they do it.
In this project, we use data from accelerometers on the belt, forearm, arm, and dumbell of 6
participants. They were asked to perform perform one set of 10 repetitions of the Unilateral Dumbbell Biceps Curl in five different fashions:

* exactly according to the specification (Class A)
* throwing the elbows to the front (Class B)
* lifting the dumbbell only halfway (Class C)
* lowering the dumbbell only halfway (Class D)
* throwing the hips to the front (Class E)

Class A corresponds to the specified execution of the exercise, while the other 4 classes correspond to common mistakes.
More information is available from the website [here](http://groupware.les.inf.puc-rio.br/har]) (see the section on the Weight Lifting Exercise Dataset).  

Goal of the project is to predict the manner in which people did the exercise ("classe" variable).

# Result

A random forest was used to predict the manner in which people did the exercise. Two models were developped: a first one based on 53 predictors (out of 159) achieving an accuracy of 99.3% and a second one based on 9 most relevant predictors achieving a 98.5% accuracy. Both models predicted correctly the 20 observations of the validation set (used for project grading). Details regarding data preprocessing, modelling and validation can be found in the Final_Report.Rmd file.

# Reference

* Ugulino, W.; Cardador, D.; Vega, K.; Velloso, E.; Milidiu, R.; Fuks, H. Wearable Computing: Accelerometers' Data Classification of Body Postures and Movements. Proceedings of 21st Brazilian Symposium on Artificial Intelligence. Advances in Artificial Intelligence - SBIA 2012. In: Lecture Notes in Computer Science., pp. 52-61. Curitiba, PR: Springer Berlin / Heidelberg, 2012. ISBN 978-3-642-34458-9. DOI: 10.1007/978-3-642-34459-6_6.
