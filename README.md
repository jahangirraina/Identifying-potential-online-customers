# Identifying-potential-online-customers
Anomaly detection for identifying potential customers from internet

# Identify potential customers
Let’s say your client is a holiday operator. They would like to advertise their trips to potential customers online. They’ve provided a sample of users that we know have bought tours from them in the past, which are saved as user_uids in conversion.csv. We would like to know which of the other users in our dataset are likely to be interested in their offers as well.

Create a model using an algorithm of your choice to predict holiday interest and populate the field pconv in submission.csv with predictions for the respective useruids given in the file.

# Data Intro
- data.csv contains raw data with user_uids and associated “segments” (variables that represent what we know about these users). Each segment is identified by an ID and you will find a corresponding label in the taxonomy.csv file. The segments are also marked as P (when a user had the opportunity to click on an option in the quiz) and A (when the user actually clicked on an option in the quiz). Some segments are represented by binary variables, others by continuous variables.
- taxonomy.csv gives category labels for the variables in data.csv. Labels have an intrinsic hierarchy delimited by § characters.
- conversion.csv represents conversion data we may receive from a client. These are customers that we know have purchased a product of interest in the past.
- submission.csv lists the user_ids that we would like predictions for.
