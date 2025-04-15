# News Category Classification
This project uses Machine Learning to classify news headlines into categories like politics, tech, sports, etc.

##  Models Used
- Naive Bayes
- Logistic Regression
- Decision Tree

## Dataset
Used: News Category Dataset from Kaggle

##  Workflow
1. Load & clean data
2. Preprocess text
3. Extract features using TF-IDF
4. Train models
5. Evaluate and compare

## How to Run
1. Clone the repo
2. Install dependencies: `pip install -r requirements.txt`
3. Install the dataset from kaggle using the link "https://www.kaggle.com/datasets/rmisra/news-category-dataset"
4. Paste the data in the json file `News_Category_Dataset_v3.json`
5. Open `notebooks/01_exploration.ipynb` to begin
6. Restart JUPYTER Kernel and hit Run All on the top
7. See the output in the deignated cell in the below code
8. One can access the trained data which get saved in the `models/saved_model.pkl` for further/future use.
