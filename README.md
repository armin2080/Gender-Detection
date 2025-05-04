# Gender-Detection

# Gender Prediction on Social Media

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/armin2080/Gender-Detection/graphs/commit-activity)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python](https://img.shields.io/badge/python-3.7+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23FF69B4.svg)
![pandas](https://img.shields.io/badge/pandas-%23150458.svg)

## Project Overview

This project focuses on predicting the gender of social media users (specifically Twitter and Instagram) based on the data provided. The analysis aims to explore how user information can be leveraged to identify potential behavioral patterns influenced by gender. Understanding these patterns can be valuable for businesses seeking insights from social media data.

## Problem Statement

Social networks serve diverse purposes, ranging from entertainment to identifying behavioral trends. Analyzing user opinions can reveal business weaknesses. Gender is a significant factor influencing user behavior, often leading to distinct reactions to various topics. This project addresses the task of predicting the gender of Twitter and Instagram users using a provided dataset.

## Dataset

The training dataset comprises 8000 rows and 10 columns, each offering specific information about the users.

| Column          | Description                                      |
|-----------------|--------------------------------------------------|
| `gender`        | Gender of the user (target variable)             |
| `age`           | User's age range (categorical)                   |
| `fullname`      | The name displayed on the social media profile   |
| `username`      | The user's unique username                       |
| `biography`     | The user's profile biography/description        |
| `follower_count`| The number of followers the user has             |
| `following_count`| The number of users the user is following        |
| `is_business`   | Indicates if the account is a business account   |
| `is_verified`   | Indicates if the account is a verified account   |
| `is_private`    | Indicates if the account is a private account    |

### Age Mapping

The `age` column represents age categories rather than continuous values. The mapping is as follows:

| Real Age of User | Mapped Number |
|------------------|---------------|
| Under 18         | 1             |
| Between 19 and 29| 2             |
| Between 30 and 39| 3             |
| Over 40          | 4             |

## Getting Started

To run this project, you will need to have Python installed on your system along with the necessary libraries.

### Prerequisites

- Python (version 3.7 or higher is recommended)
- Required Python libraries (install using pip):
  ```bash
  pip install pandas scikit-learn

## Installation

### Clone the repository:

  ```bash
  pip install pandas scikit-learn
 ```
## Acknowledgement

This project was completed as part of a course at [Quera.com](https://github.com/QueraTeam).
