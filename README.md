# Fake News Detection with NLP and Flask


Welcome to the Fake News Detection project, where we deploy the power of Natural Language Processing (NLP) and Flask to classify news articles as either fake or real. Our project encompasses everything from data preprocessing and model training to a user-friendly Flask web application. In this endeavor, we employ the mighty PassiveAggressiveClassifier as our trusty classifier.

## Table of Contents

- [Introduction](#introduction)
- [The Dataset](#the-dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Web Application](#web-application)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In today's world, fake news has become an ever-increasing concern. Our project strives to be part of the solution by leveraging machine learning and NLP techniques to automatically identify fake news articles. At its core, we have a powerful PassiveAggressiveClassifier that can effectively categorize news articles based on their textual content.

## The Dataset

Our project relies on a meticulously curated dataset of news articles, which you can access [here]. This dataset comes fully labeled, with each article categorized as either fake or real.

## Requirements

Before diving into our project, you'll need to ensure you have the following prerequisites:

- Python 3.x
- Flask
- scikit-learn
- pandas
- numpy

Don't worry; you can swiftly install all these dependencies by running a simple command using our `requirements.txt` file.

## Installation

Let's get you up and running with our project:

1. Start by cloning this repository to your local machine:

   ```bash
   git clone https://github.com/CodeWizardl/Fake-News-Detection-main.git
   ```

2. Navigate into the project directory:

   ```bash
   cd fake-news-detection
   ```

3. Install all the necessary packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

## Web Application

Now, let's bring the magic to life with our user-friendly Flask web application for real-time predictions:

1. Set the Flask app environment variable:

   ```bash
   export FLASK_APP=app.py
   ```

2. Kickstart the Flask development server:

   ```bash
   flask run
   ```

3. Excitingly, access our web application at [http://localhost:5000](http://localhost:5000) via your web browser.

## Deployment

When you're ready to take things to the next level and deploy our web application to a production server, consider platforms like Heroku, AWS, or Dockerizing the application for seamless deployment. Be sure to configure all the necessary environment variables for your deployment environment.

## Contributing

We warmly welcome contributions to this project! Feel free to open issues, submit pull requests, or suggest ways to make our project even better.

## License

This project is licensed under the MIT License. For the nitty-gritty details, consult our [LICENSE](LICENSE) file.

---

**Note**: This README provides a comprehensive overview of our project, with additional information about the dataset, model evaluation, and potential enhancements waiting for you in our actual GitHub repository.
