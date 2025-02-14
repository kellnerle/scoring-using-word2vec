# scoring-using-word2vec
This project analyzes corporate culture from transcripts provided by WRDS using Word2Vec and natural language processing.
This was a successful trial run with approximately 3,000 csv files containing the transcripts of financial calls which were used to train a W2V model and assign a score to each transcript based on pre-defined related words.

Key features:
Efficiently loads and processes csv files,
Prepares transcripts for NLP analysis through cleaning and tokenization,
Creates word embeddings to understand semantics by training word2vec,
Provides insight into corporate culture trends.

Future Enhancements:
Parallel processing,
Pretrained embeddings(?),
Time series analysis(?)

This code was written after reading "Measuring Corporate Culture Using Machine Learning" by Kai Li, Feng Mai, Rui Shen, and Xinyan Yan (doi:10.1093/rfs/hhaa079)
