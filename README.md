# NLP
Natural Language Processing

The main goal of this research is to see if the retailer's description can be used to infer a price category.

1. Import all modules you need: pandas as pd, numpy as np, nltk, re, all from sklearn
2. Read the data from the russian_retail.csv file: pd.read_csv. Print the first three rows of the table
Display the information about the dataset. What price categories are there in the column "price_category"? Is any additional processing needed? Display the unique values in the column "price_category". Display the number of values for each category in the column "price_category". What organizations have a price category "Неизвестно" in their data?
Remove the category "Неизвестно" from the column "price_category". Resample the dataset to balance the output classes
Now that you have removed the category "Неизвестно" and perfromed additional manipulations with the dataset, how many unique values are there for each category in the column "price_category"?
3. To convert texts into feature sets using the bag-of-words method, we must first filter the text, leaving only meaningful words. Download a set of insignificant words from the corpus for filtering with the nltk.download() command (in the window that appears, Corpora tab, stopwords item)
4. Import stopwords from nltk
5. Define filter functions
6. Copy data using function copy() into new variable and do filter function: .apply(lambda s: smth_to_words(s)). Print 3 head rows
7. Visualize regions using WordCloud. Create and generate a Word Cloud image for the column "regions". Display the generated World Cloud image
8. Visualize description using WordCloud. Create and generate a Word Cloud image for the column "description". Display the generated World Cloud image
9. Visualize other columns using any chart type. Why did you choose these particular types of charts?
