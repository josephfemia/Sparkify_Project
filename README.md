# Installations/Libraries
To run the scripts you will need Python 3. The libraries that are used within the scripts include numpy, pandas, pyspark, time and matplotlib. Make sure that you install all libraries by running: pip install [libraries name here]

Another way to install is by downloading and using Anaconda. This is my preferred way because it comes with the necessary libraries as well as jupyter notebook already installed rather than installing all one by one.

# Motivation
I was motivated to find out how I can better notice those who are about to downgrade their music service. I wanted to create a model to better predict if a user is likely to churn. Some of the main features used in the model is whether or not the user downgraded, the type of service the user receives, and the gender of the user. I think this tool can be very useful since it is designed to scale with big data. It can be used in conjunction with other tools to provide specific users a better price because they might churn.

# Descriptions
Sparkify.ipynb - The jupyter notebook that contains the model as well as all of the exploratory analysis of the data.
mini_sparkify_event_data.json - The subset of the larger dataset which to run modeling on.

# How to use the Project
In order to use the project you would need to open up the jupyter notebook and run all of the cells in the notebook. You must have the proper packages installed in order to run. I would like to make it known that making the model does take a few minutes so do not be alarmed, just let it run.

# Authors
By: Joseph Femia

# Results
My model ends up working flawlessly to predict if a user is likely to churn. This can be very beneficial for Sparkify as it will help them to identify users who are about to churn. For example, they may be able to offer them discounts to stay where they currently are. Thus, keeping the customer using their service longer. This will result in Sparkify gaining some unrealized income that they previously missed out on.

# Acknowledgements
This dataset was provided and promoted by Udacity. I wanted to say thank you to Udacity for providing this dataset.
