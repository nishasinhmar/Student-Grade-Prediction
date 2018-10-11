# Student-Grade-Prediction

This data approach student achievement in secondary education of a Portuguese school. The data attributes include student grades, demographic, social and school related features) and it was collected by using school reports and questionnaires. The dataset is provided regarding the performance in a distinct subject: Mathematics (mat). In [Cortez and Silva, 2008], the dataset were modeled under binary/five-level classification and regression tasks. Important note: the target attribute G3 has a strong correlation with attributes G2 and G1. This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades. It is more difficult to predict G3 without G2 and G1, but such prediction is much more useful

Link to the dataset : 
https://archive.ics.uci.edu/ml/datasets/student+performance

I have done exploratory data analysis for various features and done data modelling using different methods.
For accuracy, since the student-mat.csv contained 395 entries and there were quite a lot of features, the accuracy seems to be low but that becomes quite challenging even to work with these many features and less data points. 
I observe considering the mse and rmse scores; the baseline model,linear regression can even perform quite well.
See the notebook for more interesting results.
