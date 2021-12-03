" Advances in the Symmetry detector for databases developed in part during my master's thesis. Currently in developement, but with a usable version. For more information, check summary.pdf" 

" Model_Tests.ipynb : Attempts to further develop the model of the symmetry detector of the master’s thesis. The main objective of this part was to create an algorithm that would consistently find the two most important values for predicting a function of two variables, in a dataset with many features. Given, for example, {x, y, z, V(x,y)} where x,y,z ∈ [-1,1], the algorithm must be able to select the x and y features consistently. This was a straightforward task, but it got more complicated when given {x + y + z, y,  z, V(x,y)} and similar combinations. We tested methods using linear correlation, PCA and Random Forests, and concluded that Random Forests Feature Importance was the best of the three. "


" Symmetry_Detector.ipynb : The procedure of Model_Tests.ipynb was further improved and expanded in this notebook. The details of the various attempts are explained in the summary.pdf file. "


" Symmetry_Detector-Applied.ipynb : Initial Symmetry Detector. An example of application of the first general symmetry detector developed in Symmetry_Detector.ipynb. This symmetry detector is programmed to find, in general, the dominating symmetry in a database, without specifying exactly the features. One can find out those features by inspecting the results, but it is not very efficient. "


" Symmetry_Detector-Applied-2.ipynb : Improved Symmetry Detector. This detector finds the dominating symmetries and is able to tell which variables are responsible for those symmetries. In this notebook there are several examples of application. One of those is the physical process e+e- -> Z - e+e-, described in summary.pdf. The data of the physical events can be found in CSV_Events.zip, with different values of the coulplings."


"You can also find here the pre-trained models used for these codes. There is a model with 5 symmetries and a model with just reflection and none symmetry. "
