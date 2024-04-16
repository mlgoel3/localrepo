# Bloodline Project: Guardians of Truth

Welcome to the Bloodline project repository, developed by the team from IIT Mandi. Our project focuses on combating the spread of misinformation and deepfakes, providing tools to protect individuals and promote truth in the digital age.

## Introduction

In today's digital landscape, the proliferation of deepfake technology and fake news poses significant threats to society. Our project aims to address these challenges by providing innovative solutions to identify and mitigate the impact of manipulated media and false information.

## Features

### 1. Guardian and TruthGuard AI Models

#### Guardian
- Utilizes advanced AI technology to analyze images and detect deepfakes.
- Verifies the authenticity of images to ensure online presence remains genuine and secure.

#### TruthGuard
- Detects fake news articles using LSTM models trained on a comprehensive dataset.
- Employs TF-IDF vectorization and neural networks for accurate classification of news content.
- Cross-references results with a Gemini model to provide users with relevant and reliable news updates.

### 2. Sign-in Process with Secure Storage

- Implements a POST request system for user sign-in.
- Utilizes a PostgreSQL database for secure storage of user data.
- Implements bcrypt hashing to ensure password security and protection of sensitive information.

### 3. Image Verification

- Trains AI models on datasets sourced from Gen-AI models like GAN and DALL-E.
- Utilizes Clip Vit-14 model for feature extraction from input images.
- Employs fully connected neural network (FCNN) layer for accurate classification of genuine and manipulated images.

### 4. News Update Feature

- Integrates a news-bot feature to provide accurate news updates from reputable sources.
- Offers users access to reliable information for making informed decisions and understanding global events.

## Usage

To use the Bloodline project:
1. Clone the repository to your local machine.
2. Install the necessary dependencies listed in the requirements.txt file.
3. Run the application and follow the provided instructions for sign-in and usage of Guardian, TruthGuard, and news-bot features.

## Contributors

- [Team Bloodline](#) - IIT Mandi

## License

This project is licensed under the [MIT License](LICENSE).
