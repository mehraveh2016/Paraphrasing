# Paraphrasing
Paraphrase Italian texts with T5-it 

Paraphrasing by definition is the process of expressing a text or passage in other words, while preserving the meaning of the original words. It can be used to generate larger amounts of data by the reformulation of existing textual data and it may be of practical use in many applications involving the presentation of text to human users. 

Considering the large amount and daily growth of data generated in different languages, for instance Italian, Paraphrasing can be faced by means of machine learning tools, in a scenario where the importance of these techniques is increasing. In this thesis, we try to generate paraphrases by exploiting Transformer models to process texts in the Italian language.

The employed transformer model implemented is T5. It is a Sequence to Sequence model, which is trained using an  Italian dataset and is available in the HuggingFace model library. The pretrained model has been Fine-Tuned, on a collection of paraphrase pairs collected from Italian news feeds retrieved from the Web. This pre-trained model was trained on Google Cloud with 258,000 iterations.

The code is implemented in the Python language using the Pytorch framework. The evaluation of the results is carried out by the BLEU score.



