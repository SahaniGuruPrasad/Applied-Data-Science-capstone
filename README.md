# Applied-Data-Science-capstone
<h2> 🚀 SpaceX Rocket Launch Outcome Prediction 🚀 </h2>

### Objective of project
SpaceX is an aerospace company that has changed the dynamics of 
space industry by introducing a reusable rocket by advertising Falcon 
9 rocket launches on its website with a cost of 62 million dollars 
while other providers cost upward of 165 million dollars each, much 
of the savings is because SpaceX can reuse the first stage. As a Data 
Scientist of rivaling company the goal is to create a Machine Learning 
pipeline which can predict the landing outcome of first stage of 
falcon 9 by which the company can identify the right price to bid 
against SpaceX at rocket launch. <br>
<h3>Goal🎯</h3>
The Goal of this project is to build a machine learning model which can acurrately predict the Rocket Launch Outcome based on Launch site<br>
<h3> ⚙️ Tools used in this Projects ⚙️ </h3>

| SI.NO | Tools | uses |
| ----- | ----- | ---- |
| 1 | Numpy | Used in Data Manipulation |
| 2 | Pandas | Used in Data Manipulation and Analysis |
| 3 | Matplotlib and Seaborn | Used in Data Visualization |
| 4 | Plotly express and Plotly Dash | Used in Building Interactive Maps and Dashboard |
| 5 | Scikit-Learn | Building and Evaluating Machine Learning Model |

<h3>Phases of the Project 📋 </h3>
The Project have undergone with several phases:
<ol>
  <li>Data Collection ✅ </li>
  <li>Data Wrangling ✅ </li>
  <li>Data Analysis ✅ </li>
  <li>Data Visualization ✅ </li>
  <li>Model Development using Machine Learning ✅ </li>
</ol>
<h3>Summary/Break Down of Project 📜 </h3>
<h4>1. Data Collection</h4>
The Data Collection involves collecting the data from SpaceX REST APIs and Web scraping of Wikipedia website. <br><br>
<ul>
  <li><b>SpaceX Rest API</b>
    <p>The contents from Rest API is extracted by making a GET resquest using requests library and decoding the content in json format to futher converting it into a pandas dataframe.</p>
  </li>
  <li><b>Web Scraping</b>
    <p>In web scraping the data has been collected from Wikipedia where the launch records data is extracted using beautifulsoup as HTML tables and then converted into a pandas dataframe.</p>
  </li>
</ul>
<br>
<h4>2. Data Wrangling</h4>
<p>The Data Wrangling process mostly involved in cleaning and preprocessing of collected data.</p>
<ul>
  <li>In which Determination of labels for supervised models is implemented using EDA(Exploratory Data Analysis)</li>
  <li>Cleaning of dataset by handling the missing values and verification of datatypes such numerical or categorical of each column</li>
  <li>Classification of labels into 0 and 1 for binary classification</li>
</ul>
<h4>3. Data Analysis</h4>
<ul>
  <li><b>EDA with Data Viualization</b>
    <p>Showcasing the detailed results of data using catplot, scatterplot, bar chart and line chart</p>
  </li>
  <li><b>EDA with SQL</b>
    <p>Exploring and digging results from data by queries using SQL</p>
  </li>
</ul>
<h4>4. Data Visualization</h4>
<p>The Data Visualization process involves showcasing the results in visual interactive maps and Dashboard</p>
<ul>
  <li><b>Interactive Map</b>
    <p>Presenting the Launch Outcomes of each Launch Sites using Interactive map</p>
    <p>🔴 Red Marker representing Failure of Launch Outcome</p>
    <p>🟢 Green Marker representing Success of Launch Outcome</p>
    <p>Presenting the distance between each Launch Site and its proximites</p>
  </li>
  <li><b>Dashboard</b>
    <p>Showcasing the KPIs(Key Performance Indicators) in form of Dashboard</p>
  </li>
</ul>
<h4>5. Model Development using Machine Learning</h4>
<ul>
  <li>Building a Machine Learning model by implementing multiple models such as K-Nearest Neighbour(KNN), Decision Trees, Logistic Regression and Support Vector Machine</li>
  <li>Choosing the best performing model among above with an accuracy of 89%(i.e Desicion Tree)</li>
  <li>Evaluating the prediction results using best evaluation techinque such as Confusion Matrix</li>
</ul>
<h2>For Detailed Explaination of Project View the presentation pdf below 📄 </h2> <br>
<a href ="https://github.com/SahaniGuruPrasad/Applied-Data-Science-capstone/blob/main/Ds-capstone%20presentation.pdf">Applied Data Science Capstone Project</a>
