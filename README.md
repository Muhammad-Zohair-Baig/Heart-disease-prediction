<html>
  <head>
    <title>Heart Disease Prediction Project</title>
  </head>
  <body>
    <h1>Heart Disease Prediction Project</h1>
    <p>In this project our goal is to predict whether a person has heart disease or not depending upon specific features. The work flow of the project is as follows:</p>
    <ol>
      <li>First we import Heart disease data set and analyze it for missing values and understand each of the feature.</li>
      <li>We used one hot encoder to encode all the features.</li>
      <li>We trained different models on the train data set (Random Forest, KNN, Logistic Regression).</li>
      <li>We evaluated the model using precision, accuracy, and f1 score. (Greater The Precision, the recall will be lower as it will return the most sure however greater the recall lower the precision).</li>
      <li>We tuned the model by finding best tunning parameter's using grid search cv.</li>
      <li>Training after finding appropriate params reaped better results.</li>
    </ol>
    <p>Following technologies are used in this project:</p>
    <ul>
      <li>Pickle</li>
      <li>Pandas</li>
      <li>Numpy</li>
      <li>Seaborn</li>
      <li>Matplotlib</li>
    </ul>
    <p>Models used are:</p>
    <ul>
      <li>Random Forest Classifier</li>
      <li>KNN</li>
      <li>Random Forest Regression</li>
    </ul>
    <p>Model with best results:</p>
    <ul>
      <li>Random Forest Classifier</li>
    </ul>
  </body>
</html>


