## Select Paperspace test models and notebooks

I consulted with paperspace during my time at Insight Data Science. The notebooks contained in this repositoy test various word embedding strategies and machine learning models. The text classification model that I ultimately deployed using streamlit uses ELMo word embedding and a random forest model. The ELMo word embedding approach produced the best results compared to other word embedding options such as Glove and word2vec. ELMo derives context for words on a character-to-character basis, leading to better performance on short text, e.g. Google adgroups. I opted to use a random forest classifier as it produced the most accurate results with the least computational complexity. 

This presentation provides a high-level summary of the models I developed for paperspace, including a demo video of the Streamlit dashboard prior to deployment.
* [Paperspace Presentation](https://docs.google.com/presentation/d/1VgllRrJa9MQpMoks5liz4Qzs__PK4Hh_RtnSh3DAsGQ/edit#slide=id.p)
