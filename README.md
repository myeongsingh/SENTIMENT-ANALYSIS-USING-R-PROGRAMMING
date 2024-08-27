# SENTIMENT-ANALYSIS-USING-R-PROGRAMMING

# Word Cloud & Sentiment Analysis on COVID-19 Social Media Responses

This project involves performing word cloud generation and sentiment analysis on social media responses related to COVID-19. The analysis helps in visualizing the frequency of terms and understanding the overall sentiment of the public during the pandemic.

## Project Structure

- **Step 1**: Load the required R packages for NLP, text mining, and visualization.
- **Step 2**: Import the text data file (`pandemic_30052020.csv`).
- **Step 3**: Clean the text data using various text mining functions.
- **Step 4**: Create a corpus and a Document-Term Matrix (DTM).
- **Step 5**: Generate a word cloud to visualize the most frequent terms.
- **Step 6**: Perform sentiment analysis using multiple scoring methods.

## Dependencies

The following R packages are required for this project:

- `NLP`
- `tm`
- `RColorBrewer`
- `SnowballC`
- `stringr`
- `syuzhet`

You can install these packages using the command:

```r
install.packages(c("NLP", "tm", "RColorBrewer", "SnowballC", "stringr", "syuzhet"))
