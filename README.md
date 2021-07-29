# Paragraph Summarizer
A tool to summarizes your text to required number of lines. 
## Training Model 
- I followed a very simple yet state of the art modeling techique for summary generation. 
- I used NLTK library for stopwords present in english and also cosine distance function available in library. I also used Networkx Library for creating graph from similarity matrix and also implementing [Pagerank](https://en.wikipedia.org/wiki/PageRank) function available in Networkx Library.
- To train my model, I used the following:
    1. [NLTK Library](https://www.nltk.org/)
    2. [Networkx Library](https://networkx.org/)
### Steps
1. Upload text to be summarized to Google Colab
2. Importing neccessary Libraries and functions
3. Downloading stopwords from NLTK
4. Reading text from .txt file
5. Create Sentence Similarity Matrix
6. Create Sentence Similarity Graph from Sentence Similarity Matrix 
7. Creating scores from Sentence Similarity Graph
8. Finally, Sorting sentences in decreasing order of scores and append top n sentences to create summary.
Where n is number of lines you want in summary
