Description:

This section shows the backend initialization process using Flask and Pickle libraries. The trained machine learning model is loaded from the saved .pkl file, and the Flask application object is created to manage web routing and prediction requests.

This section defines URL routes for the Home, About, and FindYourCrop pages using Flask decorators. Each route renders its corresponding HTML template, enabling smooth navigation across the OptiCrop web application interface.

This section handles user input received from the crop prediction form through a POST request. Agricultural parameters entered by the user are collected, converted into numerical values, and passed to the trained machine learning model using the predict() function to generate crop recommendations.

This section starts the Flask development server using function. It enables the OptiCrop web application to run locally and allows users to interact with the crop prediction system through a browser interface.

