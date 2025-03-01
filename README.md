
  
# A Machine Learning Framework for Stroke Prediction: Balancing Precision and Recall in Healthcare Analytics

 Authors: Bianca Gușiță, Dragoș-Sebastian-Mihaly Efrem, Cristina Gușiță, Daniela Stănescu

Abstract: *Stroke prediction is an essential challenge in healthcare, where the timely identification of at-risk individuals can considerably improve patient outcomes and reduce long-term disabilities. In this work, we propose a comprehensive machine learning framework to predict stroke occurrence using a Kaggle dataset that integrates a wide array of health and demographic features. The dataset poses significant challenges due to a severe class imbalance, with stroke cases representing only 4.9% of the overall samples. We evaluate multiple predictive models including Logistic Regression, Support Vector Machines, Random Forests, K-Nearest Neighbors, Naive Bayes, and an LSTM-based Neural Network specifically adapted to process tabular data. Our innovative approach involves reshaping the traditional tabular inputs into a pseudo-sequential format, thereby enabling the LSTM model to capture subtle relationships between risk factors such as age, blood pressure, glucose levels, and lifestyle habits. Experimental results, measured by robust metrics such as the F2-score and Matthews Correlation Coefficient (MCC), indicate that the LSTM-based model achieves superior performance compared to conventional classifiers, particularly in balancing recall and precision. Overall, our framework not only enhances stroke prediction accuracy, but also provides valuable insights into the interdependencies of various risk factors, offering a promising tool for healthcare professionals to implement early intervention strategies and ultimately improve patient care.*

  

- The `master` folder contains the code necessary to run the master notebook, which represents a notebook that allows for the training of multiple models, each configured accordingly. Inside the folder, there are two files: one labeled `NN` and the other labeled `non-NN`. That's because separate master notebooks have been used for training and evaluating neural network models and non-neural network models.

- The `worker` folder contains the code necessary to run the worker notebook, which represents a general pipeline of how the training process should be done. It is also responsible with recording results for each instance ran. Like the `master` folder, there are two types of worker notebooks: `NN` and `non-NN`.

- The `dataset` folder contains the stroke prediction dataset in original (`healthcare-dataset-stroke-data.csv`) and the splitted versions (labeled with _train, _val and _test). The splitted versions are present to better allow researchers to compare with our work.

  

This code is licensed under the [MIT license](https://choosealicense.com/licenses/mit/).