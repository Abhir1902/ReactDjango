# API Platform with Financial Aid Classification
---
## Project Overview

This project, developed by Abhir Mirikar and Mukta Joshi, is a comprehensive platform designed to provide developers with access to various dummy APIs and their related information. The platform includes a mix of paid and freemium APIs, offering a simulated environment for developers to experiment and integrate these APIs into their applications.

One of the key features of this platform is its capability to offer dummy financial aid to users, enabling them to access paid APIs. The financial aid approval process is powered by a K-Nearest Neighbors (KNN) algorithm, which classifies whether the financial aid should be granted based on user-provided text and predefined rules.

## Features

- **Diverse API Collection**: Access a variety of dummy APIs, categorized into paid and freemium tiers.
- **Financial Aid Provision**: Simulated financial aid to help developers use paid APIs without real costs.
- **KNN Algorithm for Classification**: An intelligent system that determines financial aid approval based on user input and specific criteria.

## Project Architecture


## Installation

To set up the project locally, follow these steps:

1. Clone the repository: git clone https://github.com/Abhir1902/ReactDjango.git
2. cd ReactDjango
3. To start server : python manage.py runserver (under Server directory)
4. To start the client (under Client directory)
   i. To install the dependencies : npm install
   ii. To start the client : npm start

## Usage
1. Browse APIs: Explore the available APIs and their details through the platform interface.
2. Request Financial Aid: Submit a request for financial aid by providing the necessary information.
3. Approval Process: The KNN algorithm will evaluate your request and classify it as approved or denied based on the input and rules.

## KNN Algorithm Details
The K-Nearest Neighbors (KNN) algorithm used in this project is designed to classify financial aid requests effectively. It considers various factors from the user-provided text and applies predefined rules to make an informed decision.

1. Training Data: The algorithm is trained on a dataset containing examples of approved and denied financial aid requests.
2. Feature Extraction: Relevant features are extracted from the user input to aid in the classification process.
3. Classification: The algorithm assigns a classification based on the closest matches in the training data

## Contribution
We welcome contributions from the community. To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes and push the branch to your fork.
4. Submit a pull request with a detailed description of your changes.


## Contact
For any questions or feedback, please feel free to contact us at abhir.mirikar@gmail.com


We hope this platform helps developers to innovate and experiment with APIs in a risk-free environment. Happy coding!


Abhir & Mukta
