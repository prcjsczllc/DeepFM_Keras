# DeepFM_Keras
a model of deepfm using keras

# How to use
* you should config the columns of your data in **config.py**.
you should specified the numeric columns and categorical
columns of your data
* you can preprocessing your data in **datapreprocssing.py**.and
the function **preprocess()**used to feature engineering.the function
**preprocess_data()**used to caculate the number of values of each 
 categorical columns
* you input data must be a list of numpy array([np.array(),np.array(),...])
every numpy array is a feature of the data


# Exapmle
the data is [Porto Seguro's Safe Driver Prediction competition on Kaggle.
](https://www.kaggle.com/c/porto-seguro-safe-driver-prediction)

download the data and put into the data file,then you can run the
**main.py** 

# Attention
the metric is auc for this data you can change it for yourself
in the **metrics.py**

# Reference
[1] DeepFM: A Factorization-Machine based Neural Network for CTR Prediction, Huifeng Guo, Ruiming Tang, Yunming Yey, Zhenguo Li, Xiuqiang He.
