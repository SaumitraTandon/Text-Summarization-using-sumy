# Text Summarization using Sumy

This project demonstrates text summarization using the `sumy` library, specifically utilizing the `TextRankSummarizer` to generate concise summaries of text data. The dataset used in this notebook contains news articles from different categories, with a focus on business-related content for summarization.

## Project Structure

The notebook walks through the following steps:
1. **Loading the Dataset**: A CSV file `bbc_text_cls.csv` containing labeled news articles is loaded into a pandas DataFrame.
2. **Setting Up Summarization**: Using the `sumy` library, the `TextRankSummarizer` and `PlaintextParser` are configured for text summarization.
3. **Selecting a Sample Text**: A random business news article is selected from the dataset.
4. **Generating a Summary**: The `TextRankSummarizer` is used to generate a summary of the selected article, limited to 5 sentences.
5. **Displaying the Summary**: The summary is printed and formatted for better readability.

## Dataset

The dataset `bbc_text_cls.csv` contains text data labeled with different categories, including:
- **Business**
- (Other categories if applicable)

For this notebook, we focus on summarizing articles from the "business" category.

## Installation

To run the notebook, you will need the following Python libraries:
- `pandas`: For loading and handling the dataset
- `sumy`: For performing text summarization
- `textwrap`: To format the output for better readability

You can install these dependencies using the following command:

```bash
pip install pandas sumy
```

## Usage

1. Clone this repository or download the notebook.
2. Ensure the dataset (`bbc_text_cls.csv`) is in the same directory as the notebook.
3. Open the notebook and run all the cells to generate a summary of a random business article from the dataset.

## Example Output

Here is an example of a summarized text from the dataset:

```
Retail sales dropped by 1% on the month in December, after a 0.6% rise in November, the Office for National Statistics (ONS) said.
The ONS revised the annual 2004 rate of growth down from the 5.9% estimated in November to 3.2%.
The ONS echoed an earlier caution from Bank of England governor Mervyn King not to read too much into the poor December figures.
Some analysts put a positive gloss on the figures, pointing out that the non-seasonally-adjusted figures showed a performance comparable with 2003.
The November-December jump last year was roughly comparable with recent averages, although some way below the serious booms seen in the 1990s.
```

## Contributing

Contributions are welcome! If you'd like to improve the summarization process or add additional features, feel free to open an issue or submit a pull request.
