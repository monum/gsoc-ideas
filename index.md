## Ideas List for Google Summer of Code from the Mayor's Office of New Urban Mechanics

###  1. Urban Tree Canopy Detection Using Satellite and Aerial Imagery

The City of Boston's Parks Department maintains a comprehensive data set on trees in Boston. However, it's a manual and laborious process to get the data (such as  conducting site visits for tree counts) on a regular basis. We would like to explore the use of satellite and aerial imagery to get a regularly updated  census of trees across the city. We would also like to look at the feasibility of determining tree health and the variety of tree species across the city.

The ideal outcome would be 1) the creation of a new, accurate machine learning model focused on urban trees canopies, 2) the creation of a simple web interface for the Parks Department to upload new aerial imagery for analysis, and 3) the ability to the Parks Department to generate a list of statistics on tree counts to ensure that it continues to plants trees in an equitable manner across the city.

We would give this project a **medium** level of difficulty.

This project will require intermediate experience with Python, machine learning (in particular TensorFlow and training models with imagery), and limited experience with JavaScript HTML and CSS.

The core code base for the project is [Deep Forest](https://github.com/weecology/DeepForest), a machine learning library for tree crown detection. We will be partnering with the the WeEcology group at the University of Florida, in particular Ben Weinstein Ph.D. who has agreed to serve as an advisor. The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011.

### 2. Building a Web Service API for Solar Roof Potential

The Climate Planning team in the City of Boston's Environment Department is interested in building a lightweight web service API that provides data on the solar energy potential of building roofs throughout the city. The API should also provide data on how alternative energy sources could reduce a particular building's emissions footprint. In addition, we would like to build a simple web interface for a building owner to search for their property to view data on the solar potential of their roof and the impact on the emissions associated with their building's energy use.

We give this project a **medium** level of difficulty.

This project will require immediate experience with data analysis packages, GIS, and building web service APIs with either Python or Ruby (we have had good experiences wih Flask for this task).

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011.

### 3. Improved Translation on the City's 311 App with Machine Learning

In 2010, our office launched the City of Boston's 311 app (one of the first in the nation). The app allows residents to report an array on non-emergency issues (such as potholes) with their smartphones. Historically, the app has only been offered in English, and we have done some of the preliminary work to provide it in other languages. This is a very important issue to address, since up to 33% of the city does not speak English.

[Inspired by the City of San José](https://medium.com/swlh/better-language-translation-through-machine-learning-everything-i-wish-i-knew-6-months-ago-8fa212fb1731), we would like to build an API-accessible service that improves the translation of text from residents reporting issues through the 311 app. The translation service would be based on a custom. trained model using vocabulary frequently associated with City services.

We give this project a **medium to hard** level of difficulty.

This project will require intermediate experience with machine learning, building and training models with text classification, natural language processing, and Python. It will also require intermediate experience with building web service APIs with with a web framework like Flask, Django etc.

The mentors for the project will include two Program Directors at the Mayor's Office of Urban Mechanics, including one who served as a Google Summer of Code mentor at Code for America in 2011.
