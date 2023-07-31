# Semantic Text Similarity Checker

![License](https://img.shields.io/badge/License-MIT-blue.svg)

## Description

The Semantic Text Similarity Checker is a Flask-based web application that utilizes the SentenceTransformers library with the "stsb-roberta-large" model to determine the semantic similarity between two input sentences. It computes the similarity score as a percentage and provides the user with a quick understanding of how closely related the sentences are.

## Web Interface Screenshot

Here is a screenshot of the web interface of our Semantic Text Similarity Checker:

![Web App Screenshot](screenshots/web_interface (1).jpg)

## Features

- Semantic Similarity Check: The app calculates the semantic similarity between two input sentences using the "stsb-roberta-large" model from SentenceTransformers.
- User-Friendly Interface: The web interface is simple and intuitive, allowing users to input their sentences and obtain the similarity score easily.

## How to Use

1. Run the Application: Make sure you have installed the required dependencies by running `pip install Flask sentence-transformers`. Then, run the Flask application by executing `python app.py`.

2. Access the Web Interface: Open your web browser and navigate to `http://localhost:5000/`.

3. Input Sentences: Enter two sentences that you want to compare in the provided input fields. For instance, you can input the first sentence in the "First Sentence" field and the second sentence in the "Second Sentence" field.

4. Calculate Similarity: Click the "Calculate Similarity" button to initiate the computation of the semantic similarity between the two sentences.

5. View Result: The app will display the similarity percentage between the two sentences on the web page. The percentage indicates how similar the sentences are in terms of their meaning.

## Technology Stack

- Python
- Flask
- SentenceTransformers

## Installation

To run the application locally, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/your-username/semantic-text-similarity.git
   cd semantic-text-similarity
   ```

2. Install the required dependencies:

   ```
   pip install Flask sentence-transformers
   ```

3. Run the Flask application:

   ```
   python app.py
   ```

4. Access the web app in your browser at `http://localhost:5000/`.

## Contributing

Contributions to this project are welcome! If you have ideas for improving the app or adding new features, feel free to fork the repository and submit a pull request.

## License

This project is open-source and is licensed under the MIT License. You can find the full license text in the [LICENSE](LICENSE) file.

## Contact

For any questions or inquiries, please contact:

- Name: [Rutik_parab]
- Email: [rutikparab6@gmail.com]

---
