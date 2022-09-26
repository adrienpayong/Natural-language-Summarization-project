# Introduction to Text Summarization using Transformers
In data science, summarization has been and will likely remain a subject of intense interest.
Summarization is a method for shortening a text without losing its essential content.
It's a hot topic in Natural Language Processing (NLP). There are two types of summarization methods, depending on whether or not the original text's sentence structure is preserved. New sentences are generated using NLP techniques, extractive, and abstractive summarization. 
## Extractive Text Summarization
In extractive summarization, the most significant sentences from an article are chosen and put logically.
The sentences used to create the summary are taken verbatim from the original text. 
## Abstractive Text Summarization
An NLP task aims to generate a concise summary of a source text. Abstractive summarization does not simply copy essential phrases from the source text but also potentially develops new relevant phrases, which can be seen as paraphrasing.
## BART for Summarization of Text Data
BART stands for Bidirectional and Auto-Regressive Transformer. Its primary features are a bidirectional encoder from BERT and an autoregressive decoder from GPT. The encoder and decoder are united using the seq2seq model to form the BART algorithm. Let us look at it in more detail.
### BART Model Architecture.
To understand the BART transformer, one needs to closely look at BERT and GPT. BERT performs the Masked Language Modelling with the help of its bidirectional transformer and predicts the missing values. On the other hand, GPT uses its autoregressive decoder to predict the next token in a sentence. Merging both of these results in the BART model, as depicted in the image below.
