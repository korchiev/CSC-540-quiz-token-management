# Quiz Token Generator

This Python script generates a set of random tokens and saves them to a Word document and a CSV file. It can be used for quiz or token generation purposes.

## Usage

1. Clone this repository to your local machine:

```bash
git clone https://github.com/yourusername/quiz-token-generator.git
```

2. Install the required Python libraries if you haven't already:
``` bash
pip install python-docx pandas
```

## 'random_token_generator.py`


Configuration
You can customize the script by modifying the following variables in the `random_token_generator.py` file:

`num_strings`: The number of random tokens to generate.
`quiz_number`: The quiz number or identifier.
`font_size`: The font size for the tokens in the Word document.
Output
After running the script, you will find the following output files in the quiz_tokens directory:

`quiz_{quiz_number}_tokens.docx`: The Word document containing the generated tokens.
`quiz_{quiz_number}_tokens.csv`: The CSV file containing the generated tokens.
Feel free to adjust the script and its configuration to meet your specific requirements.


## 'token_matcher.py`

### Configuration of `token_matcher.py`
You can customize the script by modifying the following variables in the compare_csv_data.py file:

+ csv_file1: The path to the first CSV file.
+ csv_file2: The path to the second CSV file.
+ column_to_compare: The name of the column used for comparison.

Output
After running the script, you will find the following output file in the project directory:

`non_matching_rows.csv`: The CSV file containing the non-matching rows between the two input CSV files.
Feel free to adjust the script and its configuration to meet your specific requirements.
