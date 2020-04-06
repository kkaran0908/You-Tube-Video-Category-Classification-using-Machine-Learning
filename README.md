# You-Tube-Video-Category-Classification-using-Machine-Learning
![alt text](https://raw.githubusercontent.com/kkaran0908/You-Tube-Video-Category-Classification-using-Machine-Learning/master/youtube.jpg)
### Steps and Models used
-  Scrap the data from youtube.
- Preproess the data
- I have applied two different kinds of model such as LSTM, BiLSTM, Logistic Regression, Random Forest
- We have done some feature engineering as well by combining the title of the video with the description part of the video
- We are getting optimal results when using LSTM.
- You can check the results, in different notebook files.

### File Description
1. youtubedata.csv is containing the raw dataset obtained from youtube, cleaned_data.csv is containing the cleaned dataset after performing the data preprocessing. For data preprocessing you can see Data Cleaning.ipynb
2. Modeling with Title.ipynb is containing the classical machine learning models using Title only.
3. Modeling with Title + Description.ipynb is containing the classical machine learning models by featurizing the title+description.
4. Modeling with Title + Description using LSTM.ipynb is containing the LSTM model for classification.
