# Main Objective.

The Main Objective of our Project to built the Streamlit app to detect the optical glaucoma condition like normal or affected with the help of Deep Learning algorithm like CNN.


## Procedure to Shown the Result

* We have collected all the publicly available labelled(glaucoma or normal) fundus images of eye from web.

* Here, we collect the image of Gluacoma like 92 images in the format of jpg File.

* Here, we collect the image of Normal like 92 images in the format of jpg File.

* Here, we use the Deep Learning algorithm loke CNN to trained our dataset.

* We used keras (2.4.3) and tensorflow (2.3.0) on top of python (3.11).

* We trained on train set and validated on validation set after each epoch. Finally tested the test set.

* It gave 93 percent AUC score, some good accuracy, precision and recall values. We saved the model file(h5) for further usage.

* Then we built a simple streamlit app for hosting on web.


# To run this app

```
pip install -r requirements.txt

streamlit run glaucoma_app.py

```

# Requirements Installation

pip install streamlit
pip install tensorflow