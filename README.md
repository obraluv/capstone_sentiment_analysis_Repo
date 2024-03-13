This program analyses sentiment of consumers product review. Dataset is retrieved from Kaggle, it's a list of consumer reviews for Amazon products like the Kindle, Fire
TV Stick, and more. 
The dataset has a total of 24 columns and 28332 data entries
ranging from 0 to 28331. The columns include basic product information, rating, review
text, brand, reviews date and more for each product.

Spacy was imported to process our datasets but before that, the first thing to do
was Data preparation and this was done by firstly loading the dataset with pandas, had
a look through of the dataset to get more information and better understanding and to
decide which column will be relevant for the analysis.
 Secondly, an initial Data cleaning was performed, this is merely selecting the relevant
column for the analysis and dropping other columns.
 After this, NLP preprocessing was initialized by firstly defining the preprocessing
function and applying the preprocessing functions to a few samples of the dataset.

To evaluate results, packages like TextBlob was imported to analyze polarity while
wordcloud and matplotlip were used to visualize results.
