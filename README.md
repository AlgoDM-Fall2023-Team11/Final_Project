
# Capstone Project
Starbucks promotion and user demographics descriptive and predictive analysis

# Project Statement
Once every few days, Starbucks sends out an offer to users of the mobile app. An offer can be merely an advertisement for a drink or an actual offer such as a discount or BOGO (buy one get one free). Some users might not receive any offer during certain weeks. Not all users receive the same offer, and that is the challenge to solve with this data set.

The task is to combine transaction, demographic and offer data to determine which demographic groups respond best to which offer type. This data set is a simplified version of the real Starbucks app because the underlying simulator only has one product whereas Starbucks actually sells dozens of products.

# Metrics
The metric that we'll be optimizing for is the amount each customer spends upon receiving an offer, since it allows us to eventually define thresholds to sending offers and being profitable at the individual level.

# Files Description
Starbucks_Capstone_notebook.ipynb is the notebook for all the analysis and documentation of the developed solutions
app.py contains the main code for running the web app
requirements.txt contains list of dependencies for running the notebook and web app
docker-compose.yml and Dockerfile are used to create the docker image to run the web app
utils holds the utility functions used by the web app
charts.py contains code for creating the visualizations
extract_transform.py contains code for managing extraction and transformation tasks on the data
inference.py contains code for making the predictions
models is the folder containing all fitted models used for inference
data contains all the datasets used for the project (more details are provided in the notebook)
portfolio.json: containing offer ids and meta data about each offer (duration, type, etc.)
profile.json: demographic data for each customer
transcript.json: records for transactions, offers received, offers viewed, and offers completed

# Getting Started
Running locally:-
You can also run the app locally without docker. For that, you'll need a basic installation of conda and the aditional packages listed in requirements.txt (plotly, xgboost, seaborn and streamlit).

After installing this library, you run the following command in the terminal inside the folder will open the web app

# Codelabs link
Further details about the project can be found in the link below
https://codelabs-preview.appspot.com/?file_id=1V_ogqaRsbhKdiw7cIu-7DKomqE3N1gHrbkOro3XQQYc#0
