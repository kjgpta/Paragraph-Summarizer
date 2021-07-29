# Paragraph Summarizer
A tool to summarizes your text to required number of lines. 
## Training Model 
- I followed a very simple yet state of the art modeling techique for summary generation. 
- I used [NLTK library](https://www.nltk.org/) for stopwords present in english and also cosine distance function available in library. I also used [Networkx Library](https://networkx.org/) for creating graph from similarity matrix and also implementing [Pagerank](https://en.wikipedia.org/wiki/PageRank) function available in [Networkx Library](https://networkx.org/).
- To train my model, I used the following: