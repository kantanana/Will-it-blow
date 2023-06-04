# Will-it-blow

# Problem Statement
- We aimed to attempt predicting the popularity of a new movie before its production and release
- This could enable filmmakers and production companies to:
1. Make informed decisions about their movie projects
2. Allocate resources effectively
3. Increase the chances of producing successful and popular movies


# Solution
- We have thereby come up with a machine learning model that predicts the popularity of a new movie based on various features, such as the budget, release year, genre, director, and cast
- Leveraging historical movie data via the use of these features enables our model to provide an estimate of the movie's popularity before its release
- Filmmakers and production companies can use this prediction to create and publish better movies that audiences will enjoy more, thus benefiting the industry

# Role of AI (Machine Learning)
- AI in the form of a machine learning model plays a crucial role in our solution
- Training a machine learning model on a dataset of historical movie data enables us to capture patterns and relationships between movie features and popularity
- This trained model can then be used to predict the popularity of new movies based on previously mentioned pointers
- Via leveraging data-driven insights, this could help us to make accurate predictions, providing valuable insight for filmmakers and production companies during their decision-making process

# Reason for model chosen
- using a simple regression model with a single output neuron. The model predicts a continuous value, which corresponds to the movie rating.
- we define a Sequential model with a Flatten layer to flatten the image data, followed by a Dense layer with 64 neurons and a ReLU activation function
- A Dropout layer is added to prevent overfitting, and finally, we have an output Dense layer with a single neuron.
- The model is compiled using the Adam optimizer and mean squared error (MSE) loss function, which is suitable for regression tasks.

