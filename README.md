# Random Coin Flip Simulator
#### *(A Streamlit Web App)*

This repository contains the code used to build a web app via Streamlit. The final product is an interactive app that simulates random coin flips to demonstrate the law of large number: a principle in probability that states that as the number of trials of a random event increases, the average of the results will get closer to the expected value.

This app is run on Render. [Check it out here!](https://random-coin-flip-app.onrender.com)

## Features

- For a given experiment, select the number of trials (coin flips) to run.
- Visualize how the mean probability of flipping heads changes across trials as more trials are run (in a line graph).
- Keep track of the final mean probability of flipping heads and the number of trials run for each experiment in a table the records your results.

## Python Libraries Used

- `pandas==1.3.1`
- `scipy==1.6.2`
- `streamlit==1.33.0`

## How To Access The App on the Web

This web app is hosted and deployed via Render. Anyone can access it at this link: [https://random-coin-flip-app.onrender.com](https://random-coin-flip-app.onrender.com).


## How to Launch The App Locally

To launch this app locally, follow these instructions:

1. Clone the repository to your local machine by entering the following command in terminal:

git clone https://github.com/natalie-cullings/random-coin-flip-app

2. Navigate to the project directory in terminal:

cd <PATH TO DIRECTORY HERE>

3. Install the required Python libraries by running the following command in terminal:

pip install -r requirements.txt

4. Launch the app via terminal using Streamlit:

streamlit run app.py

5. Open your web browser and visit http://localhost:8501 to access the dashboard locally.

Now you can simulate random coin flips on your local machine to your heart's content. :)
