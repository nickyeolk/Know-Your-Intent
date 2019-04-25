# Know your Intent : Intent Classification Using Semantic Hashing
This project builds upon the forked repository to experiment with different methods of classifying intent. A variety of different methods were tried, and average results reported below. The BERT model was able to match the average state of the art results at 0.92.
The original repo was based on the implementation of [Subword Semantic Hashing for Intent Classification on Small Datasets](https://arxiv.org/abs/1810.07150).  

## Methods tested
1. tfidf baseline model
2. Comparing cosine distance of averaged word vectors
3. BERT pretrained model, Chatbot:1.0 AskUbuntu:0.91 WebApplication:0.86 Average:0.92  
  
Reference:
```
@article{shridhar2018subword,
  title={Subword Semantic Hashing for Intent Classification on Small Datasets},
  author={Shridhar, Kumar and Sahu, Amit and Dash, Ayushman and Alonso, Pedro and Pihlgren, Gustav and Pondeknath, Vinay and Simistira, Fotini and Liwicki, Marcus},
  journal={arXiv preprint arXiv:1810.07150},
  year={2018}
}
```

------------------------------------------------------------------------------------------------------------------------------
### Dataset

Intent Classification using Semantic Hashing as Featurizer was used. We successfully achieved State-of-the-Art results in three datasets: 
1. [Ask Ubuntu Coprus](https://github.com/sebischair/NLU-Evaluation-Corpora)
2. [Web Application Corpus](https://github.com/sebischair/NLU-Evaluation-Corpora)
3. [Chatbot Corpus](https://github.com/sebischair/NLU-Evaluation-Corpora)

Read about the details in this [blog](https://medium.com/@shridhar743/know-your-intent-sota-results-in-intent-classification-8e1ca47f364c)

------------------------------------------------------------------------------------------------------------------------------

### Results

The results were compared with other NLU service providers like Google DialogueFlow, IBM Watson, Recast AI, Botify, RASA, Snips and so on and a comparison was drawn:


![Comparison Results Table](./table/ComparisonTable.png)

-----------------------------------------------------------------------------------------------------------------------------

### Contact

For any queries, contact: shridhar.stark@gmail.com

-----------------------------------------------------------------------------------------------------------------------------
