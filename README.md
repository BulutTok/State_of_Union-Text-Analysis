

# State of the Union Text Analysis

This project analyzes the text of State of the Union addresses using text mining techniques. The analysis includes cleaning and preprocessing the text, identifying frequent words, and visualizing important words using TF-IDF and word counts per decade and president.

## Project Structure

- **Task 1**: Install and load required packages.
- **Task 2**: Load the dataset.
- **Task 3**: Inspect the dataset.
- **Task 4**: Select relevant columns.
- **Task 5**: Clean the text by fixing contractions.
- **Task 6**: Tokenize the text into words and filter out undesirable words.
- **Task 7**: Count word frequencies.
- **Task 8**: Compute TF-IDF for words.
- **Task 9**: Visualize important words using TF-IDF by decade and president.
- **Task 10**: Analyze and visualize popular words per decade.

## Installation

To replicate this analysis, you need to have R installed on your machine. Install the required packages using the following commands:

```r
install.packages('tidyverse')
install.packages('tidytext')
install.packages('sotu')
install.packages('dplyr')
```

## Usage

1. **Load and Preprocess Data**:
   - Load the State of the Union text data using the `sotu` package.
   - Select relevant columns: speech_id, president, year, text.
   - Clean the text by fixing contractions.

2. **Text Cleaning and Tokenization**:
   - Fix contractions in the text.
   - Tokenize the text into individual words.
   - Remove stop words and undesirable words.

3. **Analysis**:
   - Count the frequency of words in the text.
   - Compute the TF-IDF for words to identify important words per decade and president.
   - Visualize the most frequently used words and important words using TF-IDF.

4. **Visualization**:
   - Create bar plots to show the most frequently used words.
   - Visualize important words using TF-IDF by decade and president.
   - Analyze and visualize popular words per decade.




## Contributing

If you have any suggestions or improvements, feel free to open an issue or submit a pull request.


