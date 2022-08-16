# Drug-Review-Classification
## Final Project for DS4400 at Northeastern University

### Mirah Gordon, Genny Jawor, Caterina Wang

Final project utilizing machine learning models and various Python libraries (pandas, numpy, matplotlib, nltk, sklearn) in order to classify the efficacy of a given drug for a given condition based on thousands of user reviews from drugs.com.

The dataset was sourced from the [UCI Drug Review Dataset](https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29) and includes 215,000 rows with 6 attributes (drug name, condition, date, review, rating, useful count).

Two jupyter notebooks contain all the necessary code for this project:

* ML Final Project (Cleaning) - has code for loading in data, doing preliminary data exploration, cleaning and filtering data (including using nltk sentiment analysis on reviews), and finishing up by pre-processing the filtered dataset. The result of this notebook are four csv files which are cleaned and pre-processed and ready to be used in the second notebook.

* ML Final Project (Models) - has code for splitting the pre-processed data into training and testing sets, standardized the train and test data, and all 6 models employed in this project. It also includes metrics for analyzing each model and finally has visualizations of results and analysis.

Other documents included in this repository are the output csv's from data cleaning and the final project report that was submitted.

For access to drugs_clean.csv to load in to the cleaning notebook, click the below link for a shareable google drive file:

[drugs_clean.csv](https://drive.google.com/file/d/1oczqQdNmKpjXpzi4ZjZOOem9JlRXmZAk/view?usp=sharing)

Links to our presentation and video recording are below:

[Presentation](https://docs.google.com/presentation/d/1oK6h0p7kYjFIcyQdXBHK1VYijZ7AbsI724c7ithJ06s/edit?usp=sharing)

[Video Recording](https://youtu.be/bgONHXgaTMA)
