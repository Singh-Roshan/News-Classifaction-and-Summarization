# Automatic-News-Classifaction-and-Summarization

:+1:	Given a set of documents and their corresponding labels developed a model that can classify them into their respective categories. <BR>  :+1: Implemented classification using Google’s Bert & Supervised algorithms like Neural Network, Random Forest, SVM, Naive Bayes with an accuracy of 90% to correctly predict the label on the data corpus of 1.8 million NYT articles.<BR>
:+1: Utilized word embedding such as Tf-IDF, Google word2vec to perform the semantic analysis and calculate the similarity of these articles by projecting them into their vector space. <BR> :+1: Generated a summary using Text Teaser Algorithm based on four features such as sentence length, sentence position, keyword frequency, and text-features.
  
##  Best Model: Google's BERT

What is Google's Bert?<BR>
:zap: BERT is a method of pre-training language representations, meaning that we train a general-purpose "language understanding" model on a large text corpus (like Wikipedia), and then use that model for downstream NLP tasks that we care about (like question answering).<BR> BERT outperforms previous methods because it is the first unsupervised, deeply bidirectional system for pre-training NLP. <BR> Unsupervised means that BERT was trained using only a plain text corpus, which is important because an enormous amount of plain text data is publicly available on the web in many languages.<BR>
:zap: In traditional model such as Recurrent Neural Network,a single word is first embedded and then converted to hidden state(ho) with neural network.<BR>
:zap: Similarly, second word will again go through the same step and generate hidden state(h1) and so on h2, h3 etc.<BR>
:zap: The last hidden state along with current word will then fed to decoder which will generate the next word and one hidden state.<BR>
:zap: Each single word prediction go through a long path of hidden states which sometimes loses information and inorder to overcome the long range dependency, we use Google's Bert Model which uses attention layer. So because of attention model, current state can go through any hidden state and get the info.<BR>
:zap: Example: to predict some word "eat", it will go to all encoding hidden state and generate some key value pair, the hidden state with max value will be selected.<BR>
:zap: For more detail on Bert Model: https://github.com/google-research/bert
  
  <img src="https://user-images.githubusercontent.com/47465548/73316538-303e2100-4201-11ea-9c64-9be191583dd3.png" width="90%"></img>
  
  Demo: http://bit.ly/2Xiy3tW
