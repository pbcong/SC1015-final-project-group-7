# SC1015-final-project-group-7
# Introduction 
This is our (FCS3 Group 07) mini-project for SC1015 Data Science & Artificial Intelligence 2024. This project aims to explore the relationship between a song's inherent characteristics and its success. 
The dataset we will be using is [30000 Spotify Songs](https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs) from [Kaggle](https://www.kaggle.com/).

By exploring the data set and building machine learning models for predicting the track_popularity, we hope to gain insights into what factors contribute to a song's popularity and success.

![image](https://github.com/pbcong/SC1015-final-project-group-7/blob/main/Screenshot%202024-04-24%20192949.png?raw=true)

# Problem Statement
### Can we predict the popularity of a song based on their various features?

# Contributors 
<ul>
  <li>Pham Ba Cong: Exploratory Data Analysis, Data Preprocessing, Machine Learning</li>
  <li>Nguyen Van Thang: Exploratory Data Analysis, Create slides and script</li>
  <li>Pham Nguyen Vu Hoang: Data cleaning, Create slides and script</li>
</ul>

<h2> Library/packages </h2>
<ul>
  <li>Numpy</li>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Scipy</li>
  <li>Sklearn</li>
  <li>XGBoost</li>
</ul>
    
<h2>Models used</h2>
<ul>
  <li>LinearRegression</li>
  <li>ElasticNet</li>
  <li>Lasso</li>
  <li>RidgeGradientBoostingRegressor</li>
  <li>SGDRegressor</li>
  <li>BayesianRidge</li>
  <li>RandomForestRegressor</li>
  <li>LGBMRegressor</li>
  <li>KernelRidge</li>
  <li>XGBRegressor</li>
</ul>

<h1> Conclusion </h1>
<h2>Key Findings and Project Limitations</h2>
Our exploration of the 30,000 song dataset yielded valuable insights, but also highlighted limitations that future efforts can address:
<ol>
  <li>
    <p style="font-weight:bold"> Temporal Focus: </p> The majority of songs belonged to the post-2010 era. This suggests the model's predictions might be more applicable to contemporary music.
  </li>
  <li>
    <p style="font-weight:bold"> Artist Influence: </p> A strong correlation emerged between past artist performance and the popularity of new songs. This underscores the importance of artist reputation in influencing success.
  </li>
  <li>
    <p style="font-weight:bold"> Genre Trends: </p> Pop music dominated the dataset in terms of popularity, while rock held the least prominent position. However, these findings may not reflect the broader musical landscape.
  </li>
  <li>
    <p style="font-weight:bold"> Model Accuracy: </p> While the model captured some aspects of song popularity, its limitations require further development for practical use. Predicting the success of artistic works is inherently complex, as numerous factors beyond the scope of our data (marketing, catchiness, regional appeal) play a role.
  </li>
</ol>
These insights provide a foundation for future iterations of the project.

<h1> Future improvements: </h1>

<h2> External Data Integration: </h2>
<p> Go beyond the initial 30,000 song dataset by incorporating external sources. This could include: </p>
<ul>
  <li>
    <p style="font-weight:bold"> Artist Demographics: </p> Include region of origin, genre popularity in specific regions, and artist's historical performance data.
  </li>
  <li>
    <p style="font-weight:bold"> Marketing Spend: </p> If available, incorporate data on marketing expenses associated with each song.
  </li>
  <li>
    <p style="font-weight:bold"> Social Media Buzz: </p> Analyze social media mentions and sentiment surrounding the song's release.
  </li>
  <li>
    <p style="font-weight:bold"> Music Theory Analysis: </p> Analyze features like chord progressions, melodic patterns, and rhythmic complexity that might influence audience perception.
  </li>
</ul>

<h2>Advanced Model Exploration:</h2>
<p>While the initial model might be simpler, let's explore the potential of more sophisticated approaches:</p>
<ul>
  <li>
    <p style="font-weight:bold"> Neural Networks: </p> Utilize deep learning models like Convolutional Neural Networks (CNNs) to directly analyze audio features. CNNs can extract complex patterns from raw audio data, potentially capturing aspects like melody, rhythm, and instrumentation that influence popularity.
  </li>
  <li>
    <p style="font-weight:bold"> Text Analysis: </p> Employ Natural Language Processing (NLP) techniques to analyze song lyrics or artist interviews. Sentiment analysis of lyrics could reveal emotional themes that resonate with listeners.
  </li>
</ul>
 
 
<p> By incorporating these enhancements, we can create a more comprehensive model that considers not just inherent song characteristics but also external factors and subjective user perception. This will lead to a more robust and nuanced understanding of song popularity. </p>

<h1>What did we learn from this project?</h1>
<ol>
  <li>Data Extraction & Cleaning</li>
  <li>Data Visualisation</li>
  <li>Uni & Multi-Variate Analysis</li>
  <li>Various machine learning models like: RandomForestRegressor, ElasticNet, XGBRegressor</li>
  <li>Feature Engineering</li>
  <li>Fine tuning the hyperparameters</li>
  <li>Other libraries like tqdm</li>
</ol>

<h1>References</h1>
<ul>
  <li>
    <p>Dataset: <a href="https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs">https://www.kaggle.com/datasets/joebeachcapital/30000-spotify-songs</a></p>
  </li>
  
  <li>
    <p>
      Jason Brownlee (August 17, 2020). Ordinal and One-Hot Encodings for Categorical Data. Machine Learning Mastery </br>
      <a href="https://machinelearningmastery.com/one-hot-encoding-for-categorical-data/?
    fbclid=IwAR1gMnIz348L07Bi4c8oH5KVHGiFWjVzZwURCkl6dHicX4OtHeWRfB96yzQ">https://machinelearningmastery.com/one-hot-encoding-for-categorical-data/?
    fbclid=IwAR1gMnIz348L07Bi4c8oH5KVHGiFWjVzZwURCkl6dHicX4OtHeWRfB96yzQ
      </a>
    </p>
  </li>
  
  <li>
    <p>
      JM. Hammad Hassan (October 12, 2023). Using Grid Search For Hyper-Parameter Tuning. Medium </br>
      <a href="https://medium.com/@hammad.ai/using-grid-search-for-hyper-parameter-tuning-bad6756324cc">https://medium.com/@hammad.ai/using-grid-search-for-hyper-parameter-tuning-bad6756324cc
      </a>
    </p>
  </li>
  
  <li>
    <p>
      HAINES CITY. 30000 Spotfy Songs - Inspect - Cleaning - EDA. Kaggle </br>
      <a href="https://www.kaggle.com/code/hainescity/30000-spotfy-songs-inspect-cleaning-eda/log?scriptVersionId=157115370">https://www.kaggle.com/code/hainescity/30000-spotfy-songs-inspect-cleaning-eda/log?scriptVersionId=157115370
      </a>
    </p>
  </li>
</ul>




