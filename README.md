# LLM Detect AI-Generated Text

This project aims to detect AI-generated text using various methods and libraries. The project includes data exploration, text preprocessing, and the use of Google's Gemini AI for classification.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Text Preprocessing](#text-preprocessing)
- [AI-Generated Text Detection](#ai-generated-text-detection)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To get started, clone the repository and install the necessary libraries:

```bash
git clone https://github.com/Vaibhavipowar2023/LLM-Detect-AI-Generated-text.git
cd LLM-Detect-AI-Generated-text
pip install -r requirements.txt
```

## Usage

Run the Google Colab notebook to execute the code:

```bash
jupyter notebook
```

## Dataset

The dataset consists of essays, both human-written and AI-generated. The data is provided in CSV format.

## Exploratory Data Analysis

The code performs various EDA tasks, including:

- Word count distribution
- Character count distribution
- Prompt-wise distribution of essays
- Boxplot for word count and character count

## Text Preprocessing

Basic text cleaning steps are applied, such as:

- Converting text to lowercase
- Removing extra spaces
- Removing punctuation

## AI-Generated Text Detection

Google's Gemini AI is used to classify essays as AI-generated or human-written.

## Results

The results of the classification are saved in a new column and can be exported to a CSV file.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
```

Feel free to customize it according to your specific needs.
