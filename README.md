# LLM-using-Resume-Database

In my LLM project, I embarked on the task of enhancing resume matching using state-of-the-art techniques and the Kaggle Resume Database datasets. To effectively manage large datasets, I employed the DaVinci engine and harnessed the power of multiprocessing for parallel data processing. Given the token limitation of LLM models (4097 tokens), I strategically divided the data into manageable chunks for seamless integration with the language model.

To represent resumes in a format conducive to analysis, I implemented two distinct vectorization methods: Term Frequency-Inverse Document Frequency (TF-IDF) and Doc2Vec word embeddings. TF-IDF provided a numerical representation of word importance in each document, while Doc2Vec captured semantic relationships between words in a continuous vector space.

The highlight of my project was employing cosine similarity to compare and contrast resumes. By calculating the cosine of the angle between the vectors representing each resume, I determined the degree of similarity between a given resume and the input file. This innovative approach allowed for the efficient identification of the most similar resumes within the dataset.

In conclusion, my LLM project not only showcased the power of advanced techniques like multiprocessing, TF-IDF, and Doc2Vec word embeddings but also demonstrated the practicality of utilizing the DaVinci engine to harness the capabilities of large language models for resume matching applications. The utilization of cosine similarity further enhanced the accuracy and effectiveness of the matching process, making this project a valuable contribution to the field of resume analysis and job matching.
