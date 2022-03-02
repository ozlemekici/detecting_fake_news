# Detecting_Fake_News

**What is Fake News?**
<br/>
A type of yellow journalism, fake news encapsulates pieces of news that may be hoaxes and is generally spread through social media and other online media. 
This is often done to further or impose certain ideas and is often achieved with political agendas. Such news items may contain false and/or exaggerated claims, 
and may end up being viralized by algorithms, and users may end up in a filter bubble.
<br/>

**About Detecting Fake News with Python**
<br/>
This advanced python project of detecting fake news deals with fake and real news. Using sklearn, we build a TfidfVectorizer on our dataset. 
Then, we initialize a PassiveAggressive Classifier and fit the model. 
In the end, the accuracy score and the confusion matrix tell us how well our model fares.
<br/>

**What is a TfidfVectorizer?**
<br/>
**TF (Term Frequency)**: The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.
<br/>
**IDF (Inverse Document Frequency)**: Words that occur many times a document, but also occur many times in many others, may be irrelevant. 
IDF is a measure of how significant a term is in the entire corpus.
<br/>
The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.
<br/>

**What is a PassiveAggressiveClassifier?**
<br/>
Passive Aggressive algorithms are online learning algorithms. Such an algorithm remains passive for a correct classification outcome, and turns aggressive in the event of a miscalculation, updating and adjusting. 
Unlike most other algorithms, it does not converge. Its purpose is to make updates that correct the loss, causing very little change in the norm of the weight vector.
<br/>

**The fake news Dataset**
<br/>
The dataset we’ll use for this python project- we’ll call it news.csv. This dataset has a shape of 7796×4. The first column identifies the news, 
the second and third are the title and text, and the fourth column has labels denoting whether the news is REAL or FAKE. The dataset takes up 29.2MB of space.
<br/>
