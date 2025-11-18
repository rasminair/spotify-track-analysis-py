# Analyzing Spotify track popularity using Python and Machine Learning
<h3>Project Overview</h3>

<p>Spotify has become one of the world’s most influential platforms for discovering and streaming music. With millions of tracks available, one question stands out: <b>why do some songs become popular while others remain unnoticed?</b></p>
<p>This project explores Spotify’s track metadata to uncover the key audio features that influence popularity. Using Python and machine learning, the analysis aims to identify meaningful patterns and build predictive models that shed light on what makes a track rise to the top.</p>
<h3>Tech Stack</h3>

<p>This project is built using Python and the following data analysis tools:</p>

<ul>
<li>NumPy — Numerical computations and efficient array handling</li>
<li>Pandas — Dataset loading, cleaning, and transformation</li>
<li>Matplotlib — Baseline data visualizations</li>
<li>Seaborn — Enhanced statistical plots for deeper visual analysis</li>
</ul>
<p>These tools were used for data preprocessing, handling missing values, exploratory data analysis, visualization, and correlation studies.</p>
<h3>Results & Insights</h3>
<h4>Popularity Distribution</h4>
<ul>
<li>Most tracks fall within moderate popularity levels, forming a dense middle range. </li>
<li>Extremely high or low popularity scores are uncommon, indicating that only a small portion of songs become major hits while very few go entirely unnoticed. </li>
</ul>
<h4>Danceability & Audio Feature Distributions</h4>
<ul>
<li>Features such as danceability, energy, and loudness show wide variation across the dataset.</li>
<li>No single audio feature dominates the distribution.</li>
<li>Moderately popular songs tend to exhibit higher danceability and energetic characteristics, though this trend is not absolute.</li>
</ul>
<h4>Correlation Analysis</h4>
<ul>
<li>Loudness and energy share a strong positive correlation—louder tracks tend to be more energetic.</li>
<li>Acousticness and energy show a strong negative correlation—more acoustic songs are typically less energetic.</li>
<li>Popularity itself does not correlate strongly with any single audio feature, suggesting that success is multi-factorial.</li>
</ul>
<h4>Random Forest Feature Importance</h4>

<h5>Top predictors of popularity include:</h5>
<ul>
  <li>Acousticness</li>
   <li>Tempo</li>
   <li>Duration (ms)</li>
</ul>
<h5>Secondary contributors include:</h5>
<ul>
<li>Danceability</li>
<li>Valence</li>
<li>Speechiness</li>
</ul>
<h5>Features such as key, mode, and time_signature contribute very little to the model.</h5>
<h5>This indicates that structural musical properties matter less than expressive audio features.</h5>

<h3>Predictive Model Performance</h3>
<ul>
<li>The <b>Random Forest Regressor</b> performs reasonably well at estimating track popularity.</li>
<li>However, no single audio feature determines whether a song becomes popular.</li>
<li>External factors—such as marketing, artist fanbase, and playlist placement—likely influence popularity beyond what audio features alone can capture.</li>
</ul>
